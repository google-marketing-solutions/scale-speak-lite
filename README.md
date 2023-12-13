## Scale Speak Lite

This notebook generates audio ads based on input text (ad script text) and target languages. It then uses these languages to translate and convert the text into speech with Google Cloud's Text-to-Speech API and Vertex AI.

**Requirements:**

* Google Cloud Project with enabled APIs:
    * Text-to-Speech
    * Vertex AI
* Project Billing enabled
* Python libraries:
    * `google-cloud-texttospeech`
    * `google-cloud-aiplatform`
    * `ipywidgets`

**Features:**

* Translate ad script text to multiple target languages.
* Generate Speech Synthesis Markup Language (SSML) for each language.
* Use Vertex AI's LLM to fine-tune the SSML for a more human-like speech.
* Synthesize speech for each language and voice combination.
* Download audio files for ad trafficking.
* Optionally choose a specific voice for each language.
* Optionally edit the generated SSML for each voice.

**How to use:**

1. Install required Python libraries.
2. Run all installation steps in the notebook.
3. Input your ad script text and select desired output languages.
4. The script will translate the text to the chosen languages and generate SSML for each.
5. You can choose a different voice for each language or edit the SSML further.
6. Generate audio files for download and use them in your ad campaigns.

**Customization:**

* Change the default voices used for each language.
* Modify the SSML generation parameters for specific languages.
* Add or remove target languages.

**Note:**

* This notebook is a starting point and can be further customized to fit your specific needs.

**Additional Resources:**

* Google Cloud Text-to-Speech: [https://cloud.google.com/text-to-speech/docs/libraries](https://cloud.google.com/text-to-speech/docs/libraries)
* Vertex AI: [https://cloud.google.com/vertex-ai](https://cloud.google.com/vertex-ai)
* Speech Synthesis Markup Language (SSML): [https://cloud.google.com/text-to-speech/docs/ssml](hhttps://cloud.google.com/text-to-speech/docs/ssml)