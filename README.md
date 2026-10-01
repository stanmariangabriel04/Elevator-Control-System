# Elevator Control System

A simple 2-floor elevator control system implemented on Arduino as part of an Embedded Programming course.

## Features

* Finite state machine with `IDLE`, `MOVING` and `ARRIVED` states
* Button-based floor selection
* 16×2 LCD for displaying the current/target floor
* LED floor indicators
* Buzzer notification when the elevator arrives
* Non-blocking timing using `millis()`

## Hardware

* Arduino Uno / ATmega328P
* 16×2 LCD
* 2 push buttons
* 2 LEDs
* Piezo buzzer

The project was tested in a simulated Arduino environment.
