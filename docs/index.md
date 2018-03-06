# Infinity APS

Infinity APS is a free open source DIY [oref0](https://github.com/openaps/oref0) compatible closed loop built on [Elixir](https://www.elixir-lang.org) and [Nerves](https://nerves-project.org).

By proceeding using these tools or any piece within, you agree to their copyright and release any contributors from liability.

This is intended to be a system to support a self-driven DIY implementation and any person choosing to use these tools is solely responsible for testing and implement it. While formal training or experience as an engineer or a developer is not required, what is required is a mindset to learn what are essentially "building blocks" to implement a closed loop. This is not a "set and forget" system: it requires diligent and consistent testing and monitoring to ensure each piece of the system is monitoring, predicting, and performing as desired. The performance and quality of your system lies solely with you.

### Why Does This Project Exist?

Infinity APS is a project to help people with Type 1 Diabetes "close the loop". A closed loop is a system that monitors blood sugar, insulin delivery, and other factors, predicts future blood glucose and insulin levels, and controls the flow of insulin without manual intervention.

### Project Goals

* Build a system to communicate with an insulin pump and continuous glucose monitor in order to monitor, predict and control glucose levels
* Implement monitor and control layers
* Integrate the OpenAPS prediction algorithm (oref0) to determine basal adjustments needed
* Enable people with T1D to avoid having to learn linux system administration (cron jobs, log rotation, permissions, dependency installation, etc) in order to learn and start using a closed loop system
* A power-on to functioning loop in less than 15 seconds
* Tolerance to real world conditions like sudden power loss and flaky wireless communications without corrupting the system

## Users

### What's Needed Before Installing Infinity APS

TODO

### Installation

TODO

### Usage

TODO

### Known Issues

TODO

### Troubleshooting

TODO

## Developers

### Contributing: How Can I Get Involved?

Issue submissions and pull requests are welcome.

Infinity APS is still very early in development. Your help is needed to push it from a CGM monitoring only solution to a fully closed loop.

You can:

* Join the [Type 1 Diabetes + Elixir Discord server](https://discord.gg/XfJ78mA) and learn more about how to get involved.
* Open an issue if you see something wrong or have a wish.
* If you can code and you are willing to help the project, fork it, create a new branch with the new feature or bug solution in the name and make a Pull Request. Please add tests to ensure that your code works.

Before beginning to add code it's better to talk with us, in case someone is already working on it.

### Libraries Used

Infinity APS uses the following libraries:

* [pummpcomm](https://github.com/tmecklem/pummpcomm): communication with Medtronic insulin pumps
* [Twilight_informant](https://github.com/tmecklem/twilight_informant): communication with [Nightscout](http://www.nightscout.info)
* [oref0](https://github.com/openaps/oref0): the open reference implementation of the [OpenAPS](https://openaps.org/) reference design

### What's Needed to Develop

TODO

### How to Make It Work in Development

TODO

### Parts of the System

TODO

## License

TODO
