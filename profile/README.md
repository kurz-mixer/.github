# Kurz Mixer

This is a simple stems splitter, using Apple GPU, some python server, and platform native language for Client Side.

# Summary

On the client side, i focused to keep every process offline.

## Server

It's private, but here's some requirements

```
psycopg[binary]>=3.2
torch==2.1.2
torchaudio==2.1.2
demucs==4.0.1
numpy>=1.23,<2.0
soundfile>=0.12.1
```


## Observations

I didn't create any authentication method, because the purpose is sending this app to some friends, and test the application.

Today, this work with Mac, iPad, iOS and Android.

I know i can use AI for Auth stuffs, but i keep testing in my day a day, also, my teachers are using it to.

After some feedbacks, i hope ship this with better infrastructure. For now, this depends on my simple homelab, and don't have money to spend with this project :)

I love build open source things, so yeah, i hope you enjoy.

When things get better, i can ship it to a fair price. 

Cheers
