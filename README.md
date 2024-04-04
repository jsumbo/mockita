<h1 align="center">Mockita</h1>
</a>

<p align="center">
  Mock Interview Simulator with AI-Powered Feedback
</p>

<p align="center">
  <a href="https://twitter.com/@iamjallah">
 </a>
  <a href="[https://github.com/jsumbo/mockita](https://github.com/jsumbo/mockita)">
  </a>
</p>

<br/>

## Introduction

Mockita is an interview preparation tool that provides AI feedback on your mock interviews.

You can also clone & create this repo locally with the following command:

## How it works

Mockita uses FFmpeg to transcode the raw video into MP3. Chrome, Safari, and Firefox all record with different codecs, and FFmpeg is great for standardizing them.

We then send the audio directly to be transcribed by OpenAI's Whisper endpoint, and then stream feedback from the edge using OpenAI's gpt-3.5-turbo.
