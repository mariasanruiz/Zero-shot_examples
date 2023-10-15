# ZERO-SHOT SONORIZING OF VIDEO SEQUENCES

#### Authors: María Sánchez Ruiz, Mateo Cámara and José Luis Blanco

#### Abstract: This project focuses on exploring the generation of high-quality audio from images for the automatic sonorization of video sequences, with the aim of advancing AI-generated audio. Challenges in achieving realistic audio synthesis arise from the sensitivity of the human ear and the alignment of video with audio content. We designed, built, and tested a pipeline to process video sequences using state-of-the-art AI components for video, text, and audio, based on multimodal data representations. 

#### The pipeline starts with the CLIP model for image processing and includes AudioLDM, CoCa, and VAE models to enable audio generation from images. For evaluation, we used a  novel metric called ImageBind for embedding extraction. The use of pre-trained models helps to save time and resources during the process. 
#### To ensure ease of use and collaboration, a GitHub repository is provided, providing a user-friendly platform for sound generation. The integration of audio, image, and text embeddings contributes to the development of powerful audio models. In particular, the approach of caption-based audio generation effectively captures semantic relationships, thereby enhancing the contextual relevance of audio synthesis. The inclusion of MOS ratings allows subjective opinions and different user preferences to be taken into account when evaluating the audio.
#### The proposed pipeline was able to sonorize short video sequences in a way that is consistent with user preferences. The quality of the audio delivered matched user needs and received good gradings in our subjective tests. This project will foster innovative opportunities for future research in audio generation, leading to advances in realistic and high-quality AI-generated audio. Future work shall supplement the tests included in this Thesis and implement these for real applications.
#### This project was conducted in collaboration between DTU, UPM, and AWS research teams.


## Examples of sounds generated for three different scenes of the Skyrim video game

<div class="figure">
    <table>
        <tbody>
            <!-- Row 1 -->
            <tr>
                <th>Generated Sounds</th>
                <td><b>Walking through the woods scene</b></td>
            </tr>
            <!-- Row 2 -->
            <tr>
                <th>Generated Audio 1</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_0.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 3 -->
            <tr>
                <th>Generated Audio 2</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_1.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_1.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 4 -->
            <tr>
                <th>Generated Audio 3</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_2.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_2.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 5 -->
            <tr>
                <th>Generated Audio 4</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_3.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_3.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 6 -->
            <tr>
                <th>Generated Audio 5</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_4.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_4.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 7 -->
            <tr>
                <th>Generated Audio 6</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_5.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_5.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 8 -->
            <tr>
                <th>Generated Audio 7</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_6.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_6.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 9 -->
            <tr>
                <th>Generated Audio 8</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_7.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_7.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 10 -->
            <tr>
                <th>Generated Audio 9</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_8.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_8.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 11 -->
            <tr>
                <th>Generated Audio 10</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_9.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_9.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 12 -->
            <tr>
                <th>Generated Audio 11</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_10.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_10.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 13 -->
            <tr>
                <th>Generated Audio 12</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_11.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_11.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 14 -->
            <tr>
                <th>Generated Audio 13</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_12.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_12.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 15 -->
            <tr>
                <th>Generated Audio 14</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_13.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_13.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 16 -->
            <tr>
                <th>Generated Audio 15</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_14.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_14.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 17 -->
            <tr>
                <th>Generated Audio 16</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_15.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_15.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 18 -->
            <tr>
                <th>Generated Audio 17</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_16.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_16.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 19 -->
            <tr>
                <th>Generated Audio 18</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_17.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_17.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 20 -->
            <tr>
                <th>Generated Audio 19</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_18.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_18.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 21 -->
            <tr>
                <th>Generated Audio 20</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_19.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_19.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 22 -->
            <tr>
                <th>Generated Audio 21</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_20.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_000750/ref_000750_prompts_20.wav">
                    </audio>
                </td>
            </tr>
        </tbody>
    </table>
</div>
<div class="figure">
    <table>
        <tbody>
            <!-- Row 1 -->
            <tr>
                <th>Generated Sounds</th>
                <td><b>Walking by the river</b></td>
            </tr>
            <!-- Row 2 -->
            <tr>
                <th>Generated Audio 1</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_0.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_0.wav">
                    </audio>
                </td>
            </tr>
            <!-- Repite este bloque para los demás audios en la carpeta generated_audios_000750 -->
            <!-- Row 3 -->
            <tr>
                <th>Generated Audio 2</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_1.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_1.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 4 -->
            <tr>
                <th>Generated Audio 3</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_2.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_2.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 5 -->
            <tr>
                <th>Generated Audio 4</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_3.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_3.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 6 -->
            <tr>
                <th>Generated Audio 5</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_4.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_4.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 7 -->
            <tr>
                <th>Generated Audio 6</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_5.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_5.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 8 -->
            <tr>
                <th>Generated Audio 7</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_6.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_6.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 9 -->
            <tr>
                <th>Generated Audio 8</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_7.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_7.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 10 -->
            <tr>
                <th>Generated Audio 9</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_8.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_8.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 11 -->
            <tr>
                <th>Generated Audio 10</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_9.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_9.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 12 -->
            <tr>
                <th>Generated Audio 11</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_10.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_10.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 13 -->
            <tr>
                <th>Generated Audio 12</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_11.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_11.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 14 -->
            <tr>
                <th>Generated Audio 13</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_12.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_12.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 15 -->
            <tr>
                <th>Generated Audio 14</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_13.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_13.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 16 -->
            <tr>
                <th>Generated Audio 15</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_14.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_14.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 17 -->
            <tr>
                <th>Generated Audio 16</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_15.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_15.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 18 -->
            <tr>
                <th>Generated Audio 17</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_16.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_16.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 19 -->
            <tr>
                <th>Generated Audio 18</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_17.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_17.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 20 -->
            <tr>
                <th>Generated Audio 19</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_18.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_18.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 21 -->
            <tr>
                <th>Generated Audio 20</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_19.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_19.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 22 -->
            <tr>
                <th>Generated Audio 21</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_20.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_001140/ref_001140_prompts_20.wav">
                    </audio>
                </td>
            </tr>
        </tbody>
    </table>
</div>
<div class="figure">
    <table>
        <tbody>
            <!-- Row 1 -->
            <tr>
                <th>Generated Sounds</th>
                <td><b>Opening a chest</b></td>
            </tr>
            <!-- Row 2 -->
            <tr>
                <th>Generated Audio 1</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_0.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_0.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 3 -->
            <tr>
                <th>Generated Audio 2</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_1.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_1.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 4 -->
            <tr>
                <th>Generated Audio 3</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_2.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_2.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 5 -->
            <tr>
                <th>Generated Audio 4</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_3.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_3.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 6 -->
            <tr>
                <th>Generated Audio 5</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_4.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_4.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 7 -->
            <tr>
                <th>Generated Audio 6</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_5.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_5.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 8 -->
            <tr>
                <th>Generated Audio 7</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_6.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_6.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 9 -->
            <tr>
                <th>Generated Audio 8</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_7.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_7.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 10 -->
            <tr>
                <th>Generated Audio 9</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_8.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_8.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 11 -->
            <tr>
                <th>Generated Audio 10</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_9.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_9.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 12 -->
            <tr>
                <th>Generated Audio 11</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_10.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_10.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 13 -->
            <tr>
                <th>Generated Audio 12</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_11.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_11.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 14 -->
            <tr>
                <th>Generated Audio 13</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_12.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_12.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 15 -->
            <tr>
                <th>Generated Audio 14</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_13.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_13.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 16 -->
            <tr>
                <th>Generated Audio 15</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_14.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_14.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 17 -->
            <tr>
                <th>Generated Audio 16</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_15.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_15.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 18 -->
            <tr>
                <th>Generated Audio 17</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_16.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_16.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 19 -->
            <tr>
                <th>Generated Audio 18</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_17.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_17.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 20 -->
            <tr>
                <th>Generated Audio 19</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_18.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_18.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 21 -->
            <tr>
                <th>Generated Audio 20</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_19.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_19.wav">
                    </audio>
                </td>
            </tr>
            <!-- Row 22 -->
            <tr>
                <th>Generated Audio 21</th>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_20.wav">
                    </audio>
                </td>
                <td>
                    <audio controls="">
                        <source src="generated_audios_010860/ref_010860_prompts_20.wav">
                    </audio>
                </td>
            </tr>
        </tbody>
    </table>
</div>






