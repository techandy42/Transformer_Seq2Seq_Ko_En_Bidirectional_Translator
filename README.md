# Transformer_Seq2Seq_Ko_En_Bidirectional_Translator

> About

- A bidirectional (joint model) transformer seq2seq translator model for Korean-to-English translation.
- Two encoder-decoder transformer models have been used to train Korean-to-English and English-to-Korean translators, and the translator wrapper model combines the two models together to create a bidirectional translator that can take in both Korean and English inputs.
- Trained on [Kaggle Ted-Talk Translation Dataset](https://www.kaggle.com/datasets/msarmi9/englishkorean-multitarget-ted-talks-task-mttt).
- The following results show the model trained for 10 epochs (4~5 hours of training on A100 GPU; train for longer epochs to get better performance).

> Translation Examples

- Raw translation outputs are stored in the `translated_dataset_no2_epochs_1_to_10.zip` file.

**English-to-Korean**
```

```

**Korean-to-English**
```

```

> Performance

**Average Bleu Scores**
![Results](./results_avg_bleu_scores_dataset_no2_epochs_1_to_10.png)
