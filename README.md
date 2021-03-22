# Tempo estimators comparison for EDM

This repository handles the notebook *Tempo estimators comparison*, where a four different tempo estimators are analized for EDM music and a comparison between them is done. It has been developed in the scope of a project for the Music Information Retrieval course in the Master in Sound and Music Computing, Universitat Pompeu Fabra (2021).

The *Beatport EDM key* dataset from the [mirdata library](https://mirdata.readthedocs.io/) is used, and the evaluation framework [tempo_eval](https://tempoeval.github.io/tempo_eval/).

## Use

The notebook has been done in Colab, where it is recommended to run it. There are instructions during the notebook to run it properly. Other environments can be also used, but the library and modules installation as well as the files paths have to be checked by the user.

To help in the reproduction of the notebook, some data is also provided in two different ways:
  - pkl files in the *vars* folder. They have all the tempos already readed from the dataset
  - JAMS files in the *annotations* folder. They are neccessary to create the evaluation document with the tempo_eval framework

Please, refere to the notebook to learn the use of the provided data.

## License

This project is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).
