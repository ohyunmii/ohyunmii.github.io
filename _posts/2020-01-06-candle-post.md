---
layout: post
categories: posts
title: Electric Candle
subtitle: An Electric Table Lamp for Dematerialized Candles
featured-image: /images/candle/theme.jpg
tags: [Interaction Design, HCI, Dematerialization, Tangible Interaction, Prototyping]
date-string: JANUARY 06, 2020
---


### Abstract

Dematerialization in HCI community refers to a process in which contents become disengaged from fixed carriers. In other words, contents no longer require physical medium and can rather flow freely through networks and devices [<a href="http://www.ijdesign.org/index.php/IJDesign/article/view/1124/554"> Physical Interaction in a Dematerialized World </a>]. The best exemplar of this phenomenon is CDs being replaced by digital files. 
In this project we focus on dematerialization of physical light sources. Studies on designing interaction methods for dematerialization of light is not new. However, previous studies on light dematerialization either points to emotional aspect of candle usage or introduce usage-specific interactions on screen. In contrast, the primary goal of this project is in enhancing user experience of candle lights using physical interaction design. Th electric candle light introduced in this project is a physical artifact in the form of a candle that can be lit up using finger-swipe motion. We use candle melting metaphor to implement the candle height lowering to the base level as time ticks by for following reason: it helps users to visualize energy consumption.

<br>

### System Design

<center>
	<img src="/images/candle/structure.png"  style = "width:50%"/>
</center>
<br>

### Technical Implementation
* Hardware <br>
Descending candle frame is implemented with a linear actuator with –driver and configured appropriately to be used with Arduino Nano. Two limit switches have been placed on maximum and minimum location the actuator can reach since the motor can only be driven by a positive or a negative speed. As the motor requires 12V, an external power supply is used. For candle flames, two two-legged LEDs are used. A microphone module is positioned near the 3D-printed flame for receiving blowing input. A pressure sensor along with a button switch is fixed on the bottom part of the candle frame body.
<br>
* Software <br>
The software program to control all digital and analog inputs as well as output components including button switch, limit switches, pressure sensor, LEDs, microphone, and linear actuator are all coded and managed in Arduino IDE. The code used in this project can be found <a href="https://github.com/ohyunmii/candle">here</a>.
<br>

<br>

<center>
<video width="560" height="315" controls>
  <source src="/images/candle/candle.mp4" type="video/mp4">
</video>
</center>





