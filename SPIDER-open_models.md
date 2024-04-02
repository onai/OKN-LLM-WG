# SPIDER Open Models
Below is a list of potential language models we can offer/serve as open and sustainable alternatives to commercially available services.

Alternatively, if you would like to experiment with smaller open models yourself, [Google Colab](https://colab.research.google.com/) offers a T4 GPU for free. Although it might not be available all the time as those GPUs might be prempted based on demand and availability. An example notebook is given [here](#google-colab).

## Usable Language Models

There are 3 foundational models, **Llama 2**, **Mistral**, and **Mixtral** that we can offer.

## Llama 2
Llama 2 is an umbrella term for a family of LLMs, in particular any combination of:
- **Parameters**: 7B parameters, 13B, 34B, and 70B.
- **Fine tuning data set**: programming, chatting, or following instructions.

## Mistral
Separately, there is **Mistral**, a smaller 7B model, but with extensive training data. It is fast and performs better than the corresponding Llama 2, 7B parameter models in many tasks.

## Mixtral
The large alternative to Mistral is **Mixtral**, with a different architecture totaling 8\*7B=56B. Each inference step only uses 7B parameters, which makes inference fast, yet more powerful.

None of the models perform as well as **GPT-4**, some of them are comparable to **GPT-3.5**.

![Mixtral of Experts](https://mistral.ai/images/news/mixtral-of-experts/open_models.png)
![Overview](https://mistral.ai/images/news/mixtral-of-experts/overview.png)

**Note**: *Mixtral and Llama 70B are very large models that need expensive GPUs.*

## Google Colab

[Example notebook](https://colab.research.google.com/drive/16R4S3UVkKciJLe1h6ai_syb7DoHgXKOg)

This notebook deploys [oobabooga](https://github.com/oobabooga/text-generation-webui) webui. Additionally, it sets up exllamav2 for faster inference and downloads a Llama2-13B model for you. It takes about 20 minutes to deploy on free tier notebooks.
