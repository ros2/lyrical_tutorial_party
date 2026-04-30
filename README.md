# ROS 2 Lyrical Tutorial Party

Welcome! The purpose of this repository is to guide the testing of various functionalities of ROS 2 Lyrical Luth prior to official release.
In other words, welcome to the Tutorial Party!

The tutorial party will run between April 30th, 2026 and May 14, 2026 (inclusive).
Testing after that is welcome, but will not be included in the official statistics.

ℹ️ Full details about the [Test and Tutorial Party are available on Open Robotics Discourse.](TODO) ℹ️

## Who can contribute?

Everyone, all contributions are welcome!
If you would like to be eligible for [ROS swag](https://store.openrobotics.org/collections/lyrical-luth-merch) or [OSRA membership](https://osralliance.org/) you ⚠️ [must register using this form](https://forms.gle/LQ4wNcHUZsjySsv27) ⚠️ so we can associate your e-mail address with Github handle. 
Full details about the [Test and Tutorial Party are available on Open Robotics Discourse.](TODO)

## How to contribute?

The [Issues](https://github.com/ros2/lyrical_tutorial_party/issues) page has several tickets each containing specific instructions to test a particular functionality of ROS 2 Lyrical Luth.
Each ticket will have the following sections:

1. **Setup**: Details on the desired hardware and software setup for this test. The following combinations are possible.
   1. RMW Implementation: `FASTDDS`, `CYCLONEDDS`, `CONNEXTDDS` or `ZENOH`
   2. BuildType:
      * `binary`: pre-built packaged ROS 2 workspace from [the releases page](https://github.com/ros2/ros2/releases/tag/release-lyrical-beta-20260429-1)
      * `debian`: pre-built debian packages from the apt repository
      * `source`: building your own workspace from source
   3. Os: `Ubuntu Resolut`, `Windows 11` and `RHEL-10`
   4. Chip: `Amd64` or `Arm64`
2. **Links**: Any relevant references for this test.
3. **Checks**: A list of functionalities to validate.

To contribute, first ensure if you have the relevant setup as described in the ticket.
If you don't have the setup, you can find the [installation instructions on docs.ros.org](http://docs.ros.org/en/rolling/Installation.html) 
If you would like to change your RMW vendor please [follow the instructions in the ROS documentation.](https://docs.ros.org/en/rolling/Installation/RMW-Implementations.html)
Next, assign the ticket to yourself via the `Assignees` option or comment on the ticket indicating your interest.
Then follow the instructions to perform the necessary checks. 


**All checks passed?**
Great! Please tick the checkboxes if you can or else leave a comment indicating your successful testing.
Attaching your terminal output (codeblock comment or gist file) as a form of verification is greatly appreciated.
If you have the necessary permission, go ahead and close the ticket by clicking `Close as completed`.

**Encountered failures?**
If one or more checks fail, please provide the error message in a codeblock comment or as a gist file attachment.
We also recommend that you run `ros2 doctor --report` and include the output in your report. [Report the issue on this board.](https://github.com/orgs/ros2/projects/79/views/1)

## What to prioritize?

The goal is to close all tickets after successful validation. But we would like to prioritize the following sets in order:

* RHEL 10


## What if I want to test something else?

If you would like to test the functionality of any other package or extend the capabilities tested above, please open additional tickets while following the format described above.

## Questions

Questions related to testing may be posted on the [Discussions](https://github.com/orgs/ros2/projects/79/views/1) board.
Kindly ensure to link the relevant issue ticket when starting a new discussion.
