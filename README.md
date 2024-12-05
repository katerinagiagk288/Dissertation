# Abstract
reCAPTCHA v3, Google’s latest verification system, can filter humans from illegitimate bots without
user interaction by using a risk analysis engine gathering the web client’s background data. Despite
how widespread this system has become, web clients have become suspect of whether their data is
private, and it has been criticised to being susceptible to bots, with literature showing that machine
learning techniques such as Reinforcement Learning can achieve up to 99.6% evasion rates. With
machine learning continuing to advance, these weaknesses underscore the need for a more secure
CAPTCHA solution. This project investigates a possible solution by integrating a Zero Knowledge
Proof protocol onto the domain of a One-Class Support Vector Machine (SVM). This would allow the
machine learning model to operate without revealing internal mechanisms nor the web client’s data
being used, ensuring both verification of the model but also privacy preservation. This project lays the
groundwork for a potential reCAPTCHA v4, which uses a client’s behavioural data while at the same
time preserving their privacy.
# Keywords: reCAPTCHA, machine learning, zero knowledge, zkSNARK, One-Class SVM
