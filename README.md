# snips-ASR

[snips-asr](https://docs.snips.ai/articles/platform/asr) in a docker container.

### Usage

`docker run -it -v config:/etc/snips -v assistant:/usr/share/snips/assistant r1co/snips-asr`

You have to provide a snips.toml and your assistant.

#### Volumes
* /etc/snips
    * location of `snips.toml`
* /var/lib/snips
* /usr/share/snips