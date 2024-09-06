### Abstract
One-shot voice conversion (VC) is a method that enables the transformation between any two speakers using only a single target speaker utterance. Existing methods often rely on complex architectures and external speaker embeddings derived from pre-trained speaker verification (SV) models to enhance the fidelity in converted speech. Recent works employing K-means quantization (KQ) with self-supervised learning (SSL) features have demonstrated effectiveness in capturing content information. However, they often struggle to preserve speaking variation, including prosodic details and phonetic variation that change within an utterance, particularly when using smaller codebooks. In this work, we propose a simple yet effective one-shot VC model using characteristics of SSL features and speech attributes. Our approach addresses the issue of losing speaking variation, enabling high-fidelity voice conversion trained with only reconstruction-based losses. We demonstrated the performance of our model across six evaluation metrics, and the experiments highlight the benefits of the speaking variation compensation method.
### DEMO ( Unseen Source and Target, both of them are random sampled, and converted by only one utterance)

| **Source** | **Target** | **Ours Converted** | **Chou** | **AutoVC** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="all/all/unseen/p330_p347_3/source.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p347_3/target.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p347_3/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p347_3/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p347_3/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/unseen/p347_p330_2/source.wav" controls preload></audio> | <audio src="all/all/unseen/p347_p330_2/target.wav" controls preload></audio> | <audio src="all/all/unseen/p347_p330_2/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p347_p330_2/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p347_p330_2/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/unseen/p330_p347_1/source.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p347_1/target.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p347_1/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p347_1/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p347_1/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/unseen/p330_p361_1/source.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p361_1/target.wav" controls preload></audio> | <audio src="all/all/unseen/p330_p361_1/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p361_1/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p330_p361_1/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/unseen/p347_p330_3/source.wav" controls preload></audio> | <audio src="all/all/unseen/p347_p330_3/target.wav" controls preload></audio> | <audio src="all/all/unseen/p347_p330_3/conversion.wav" controls preload></audio> |<audio src="all/all/unseen/p347_p330_3/adain/converted.wav" controls preload></audio> |<audio src="all/all/unseen/p347_p330_3/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |


### DEMO ( Seen Source and Target, both of them are random sampled, and converted by only one utterance)

| **Source** | **Target** | **Ours Converted** | **Chou** | **AutoVC** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="all/all/seen/p280_p306_0/source.wav" controls preload></audio> | <audio src="all/all/seen/p280_p306_0/target.wav" controls preload></audio> | <audio src="all/all/seen/p280_p306_0/conversion.wav" controls preload></audio> |<audio src="all/all/seen/p280_p306_0/adain/converted.wav" controls preload></audio> |<audio src="all/all/seen/p280_p306_0/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/seen/p317_p318_0/source.wav" controls preload></audio> | <audio src="all/all/seen/p317_p318_0/target.wav" controls preload></audio> | <audio src="all/all/seen/p317_p318_0/conversion.wav" controls preload></audio> |<audio src="all/all/seen/p317_p318_0/adain/converted.wav" controls preload></audio> |<audio src="all/all/seen/p317_p318_0/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/seen/p276_p243_0/source.wav" controls preload></audio> | <audio src="all/all/seen/p276_p243_0/target.wav" controls preload></audio> | <audio src="all/all/seen/p276_p243_0/conversion.wav" controls preload></audio> |<audio src="all/all/seen/p276_p243_0/adain/converted.wav" controls preload></audio> |<audio src="all/all/seen/p276_p243_0/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
| <audio src="all/all/seen/p275_p263_0/source.wav" controls preload></audio> | <audio src="all/all/seen/p275_p263_0/target.wav" controls preload></audio> | <audio src="all/all/seen/p275_p263_0/conversion.wav" controls preload></audio> |<audio src="all/all/seen/p275_p263_0/adain/converted.wav" controls preload></audio> |<audio src="all/all/seen/p275_p263_0/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |
