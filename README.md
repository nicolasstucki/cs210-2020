This repository will be used as the website for Functional Programming CS-210. It will be updated weekly throughout the semester. This README contains general information about the class.

- [previous-exams](previous-exams) contains PDFs for the previous exams.
- [exercises](exercises) contains markdown documents for the exercise sessions and solutions.
- [slides](slides) contains the slides presented in class.
- [labs](labs) contains markdown documents for the labs.

We will use GitLab's issue tracker as a discussion forum. Feel free to [open an issue](https://gitlab.epfl.ch/lamp/cs210/issues/new) if you have any comments or questions

# First-week tasks

1. [Join the Discord](https://discord.gg/8ud6UpE)
2. Log into gitlab: https://gitlab.epfl.ch/users/sign_in
3. [Register in a group](exercises/Group workspaces.md) for the exercise sessions
4. Follow the [Tools Setup](labs/tools-setup.md) page.
5. Do the [example lab](labs/example-lab.md).
6. Do the [first graded lab](labs/lab-1.md).

## Grading

The grading of the course is divided between labs (25%), exercises (5%) and a final exam (70%). There will be no midterm exam this year.

## Staff

| Role        | People |
| :---        | :--- |
| Professors  | [Martin Odersky](https://people.epfl.ch/martin.odersky), [Viktor Kunčak](https://people.epfl.ch/viktor.kuncak) |
| TAs         | [Adrien Ghosn](https://people.epfl.ch/adrien.ghosn), [Dragana Milovancevic](https://people.epfl.ch/dragana.milovancevic), [Guillaume Martres](https://people.epfl.ch/guillaume.martres), [Nicolas Stucki](https://people.epfl.ch/nicolas.stucki), [Olivier Blanvillain](https://people.epfl.ch/olivier.blanvillain) |
| Student TAs | [Arthur Vignon](https://people.epfl.ch/arthur.vignon), [Emilien Ordonneau](https://people.epfl.ch/emilien.ordonneau), [Lucas Giordano](https://people.epfl.ch/lucas.giordano), [Mohamed Dhraief](https://people.epfl.ch/mohamed.dhraief), [Sara Djambazovska](https://people.epfl.ch/sara.djambazovska) |

## Rooms

Lectures are prerecorded and published on this page.
Exercise sessions take place on Wednesdays from 13:15 to 15:00 on [Discord](https://discord.gg/8ud6UpE).
Lab sessions take place on Fridays from 10:15 to 12:00, also on [Discord](https://discord.gg/8ud6UpE).
In the first 2 weeks of the semester, in-person office hours will be held on Wednesdays from 13:15 to 15:00 in CO 2, and on Fridays from 10:15 to 12:00 in ELA1.
These office hours are there to help you setting up Git and Java our your machines and answer any other question you might have about the class. We will be happy to arrange further in-person or virtual (Discord, Zoom, etc.) office hours--just contact one of us with a list of all your available time slots.

## Lecture Schedule

<!-- date -d "30/09/2019 364 days" +"%d.%m.%Y" -->

**Note**: In some lectures, worksheets are used to present code. To learn how to
use worksheets yourselves, please follow the [Tools
Setup](labs/tools-setup.md) and [example lab](labs/example-lab.md). To create a
new empty project to experiment with worksheets, you can clone the following
repository and run `code . ` inside as usual: [`git clone https://gitlab.epfl.ch/lamp/cs210-worksheets`](https://gitlab.epfl.ch/lamp/cs210-worksheets)

| Week | Date        | Topic                       | Video              |
| :--  | :--         | :--                         | :--                |
| 1    | 16.09.2020  | Intro class                 | [Part 1][Video 1.1.1], [Part 2][Video 1.1.2], [Part 3][Video 1.1.3], [Part 4][Video 1.1.4], [Part 5][Video 1.1.5], [Part 6][Video 1.1.6], [Part 7][Video 1.1.7] |
| 2    | 23.09.2020  | Recursion / Function values | [Part 1][Video 1.2.1], [Part 2][Video 1.2.2], [Part 3][Video 1.2.3], [Part 4][Video 1.2.4], [Part 5][Video 1.2.5], [Part 6][Video 1.2.6], [Part 7][Video 1.2.7] |
| 3    | 30.09.2020  | Classes                     | [Part 1][Video 1.3.1], [Part 2][Video 1.3.2], [Part 3][Video 1.3.3], [Part 4][Video 1.3.4], [Part 5][Video 1.3.5] |
| 4    | 07.10.2020  | Classes                     |                    |
| 5    | 14.10.2020  | List                        |                    |
| 6    | 21.10.2020  | Collection                  |                    |
| 7    | 04.11.2020  | Monads                      |                    |
| 8    | 28.10.2020  | Lazy evaluation             |                    |
| 9    | 11.11.2020  | Type-directed computation   |                    |
| 10   | 18.11.2020  | State                       |                    |
| 11   | 25.11.2020  | Functional Reactive Programming and Constraint Propagation / Symbolic computation |                    |
| 12   | 02.12.2020  | Interpreter                 |                    |
| 13   | 09.12.2020  | Interpreter                 |                    |
| 14   | 16.12.2020  | Review for the exam         |                    |

## Lab Schedule

| Title                             | Start Date | Discord Session (Fridays 10:15 to 12:00) | Due Date ([AoE](https://en.wikipedia.org/wiki/Anywhere_on_Earth)) |
| :--                               | :--        | :--                     | :--        |
| Recursion                         | 16.09.2020 | 18.09.2020              | *27.09.2020* |
| Functional Sets                   | 23.09.2020 | 25.09.2020              | 01.10.2020 |
| Object-Oriented Sets              | 30.09.2020 | 02.10.2020              | 08.10.2020 |
| Huffman Coding                    | 07.10.2020 | 09.10.2020 & 16.10.2020 | 22.10.2020 |
| Anagrams                          | 21.10.2020 | 23.10.2020              | 05.11.2020 |
| Quickcheck                        | 28.10.2020 | 30.10.2020              | 12.11.2020 |
| Bloxorz                           | 04.11.2020 | 06.11.2020 & 13.11.2020 | 19.11.2020 |
| Codecs                            | 18.11.2020 | 20.11.2020 & 27.11.2020 | 03.12.2020 |
| Interpreter                       | 02.12.2020 | 04.12.2020 & 11.12.2020 | 17.12.2020 |

Labs are individual assignments where you get to write Scala programs using the concepts learned during lectures.
Labs are submitted by pushing your code on GitLab, see details in the [grading and submission](labs/grading-and-submission.md) page.

## Exercise Schedule

| Title                                          | Handout Released | Discord Session (Wednesdays 13:15 to 15:00) | Due Date ([AoE](https://en.wikipedia.org/wiki/Anywhere_on_Earth)) | Solution Released |
| :--                                            | :--              | :--             | :--              | :--              |
|  First week tasks                              | -                | 16.09.2020      | -                | -                |
| Exercise Session 1                             | -                | 23.09.2020      | 27.09.2020       | 28.09.2020       |
| Exercise Session 2                             | 28.09.2020       | 30.09.2020      | 04.10.2020       | 05.10.2020       |
| Exercise Session 3                             | 05.10.2020       | 07.10.2020      | 11.10.2020       | 12.10.2020       |
| Exercise Session 4                             | 12.10.2020       | 14.10.2020      | 19.10.2020       | 20.10.2020       |
| Exercise Session 5                             | 20.10.2020       | 21.10.2020      | 25.10.2020       | 26.10.2020       |
| Exercise Session 6                             | 26.10.2020       | 28.10.2020      | 01.11.2020       | 02.11.2020       |
| Exercise Session 7                             | 09.11.2020       | 11.11.2020      | 15.11.2020       | 16.11.2020       |
| Exercise Session 8                             | 16.11.2020       | 18.11.2020      | 22.11.2020       | 23.11.2020       |
| Exercise Session 9                             | 23.11.2020       | 25.11.2020      | 29.11.2020       | 30.11.2020       |
| Exercise Session 10                            | 30.11.2020       | 02.12.2020      | 06.12.2020       | 07.12.2020       |
| Exercise Session 11                            | 07.12.2020       | 09.12.2020      | 13.12.2020       | 14.12.2020       |

Exercises are pen and paper style questions that will prepare you for the final exam.
Exercises should be done in groups and submitted via Google Drive, see details in the [Group workspaces](exercises/Group workspaces.md) page.

## Exam Schedule

The final exam date will be during the exam session in January 2021. The final exam will cover all material seen during the semester.

Information about exam organization will be communicated by email a few days before the exam.


[Video 1.1.1]: https://tube.switch.ch/videos/7ed71e65
[Video 1.1.2]: https://tube.switch.ch/videos/eefaaa33
[Video 1.1.3]: https://tube.switch.ch/videos/7ec55c9c
[Video 1.1.4]: https://tube.switch.ch/videos/f8abe6bf
[Video 1.1.5]: https://tube.switch.ch/videos/1f8d3205
[Video 1.1.6]: https://tube.switch.ch/videos/9274e0f4
[Video 1.1.7]: https://tube.switch.ch/videos/1843caa3

[Video 1.2.1]: https://tube.switch.ch/videos/646cfe4f
[Video 1.2.2]: https://tube.switch.ch/videos/9e573d2f
[Video 1.2.3]: https://tube.switch.ch/videos/0e2be793
[Video 1.2.4]: https://tube.switch.ch/videos/ddcbb43f
[Video 1.2.5]: https://tube.switch.ch/videos/dec623bc
[Video 1.2.6]: https://tube.switch.ch/videos/6e8643cf
[Video 1.2.7]: https://tube.switch.ch/videos/dc82606b

[Video 1.3.1]: https://tube.switch.ch/videos/56c88e00
[Video 1.3.2]: https://tube.switch.ch/videos/1c969056
[Video 1.3.3]: https://tube.switch.ch/videos/d3a7aff4
[Video 1.3.4]: https://tube.switch.ch/videos/03486c5a
[Video 1.3.5]: https://tube.switch.ch/videos/82b0e104

[Video 1.1.1 back]: https://drive.google.com/file/d/1Gtz9IDWZ7aObqtsgFk7QcMkci4bKD74v/view?usp=sharing
[Video 1.1.2 back]: https://drive.google.com/file/d/1nXKcpOkXTuRtuSJcf6_E1_MSbkaaPPpm/view?usp=sharing
[Video 1.1.3 back]: https://drive.google.com/file/d/1ePJ_h7XwEcK899OWoer6Vpi4k2VQWUv4/view?usp=sharing
[Video 1.1.4 back]: https://drive.google.com/file/d/1Ud0eI2GvTMlfNBLo60ADlv6KrZygD7UX/view?usp=sharing
[Video 1.1.5 back]: https://drive.google.com/file/d/1tEU_dGRRVEHJH3magWhDSKEsW4ADOBw1/view?usp=sharing
[Video 1.1.6 back]: https://drive.google.com/file/d/1ARKcSilynOTBssFEvQ-MFc7RgKtVfqha/view?usp=sharing
[Video 1.1.7 back]: https://drive.google.com/file/d/1jbHxp5go47XBxolfGQjD7zs9fb-1sKky/view?usp=sharing

