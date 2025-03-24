---
title: "BLDC driver rant - DRV10983"
date: 2025-03-23
category: just-talking
---

A bit ago I found the DRV10983, it seemed great, it had everything integrated and was sensorless, so when I finally printed the papers and started looking into how to actually use the thing, I realized the max continuous amperage it supports would be around 2A or 3A at most.
But I got a flash hobby 2207.5 2270kv which in the specifications said it needs around 16V and 30A~60A, I knew about the voltage requirement which is why I choose the DRV10983. But I didn't realized the actual issue would be current.
Well... now I guess i have to look into making my own, alternatively I could always buy a ESC that supports this already, however this project is meant to be as DIY as I can, So I'll continue trying to do everything myself.

I still don't know exactly what I'm doing tbh, I keep reading this things but still doesn't make total sense, currently looking at the DRV8301 a gate driver IC for three-phase motors. It looks promising but I don't exactly understand it.

Anyways, the current plan is to buy some high powered MOSFETs with a battery for them and start getting a feel for what I will need to make in the circuit. So for now I need to also get some high powered batteries to test this out. That I will not be DIWhying.

... A bit later

So anyways, tried soldering some jumper wires to my motor to see if I could detect the Back-EMF and aside from noise, couldn't detect a single thing. Unfortunate I'll have to wait for the MOSFETs and battery before I can start testing more things with the motor.
