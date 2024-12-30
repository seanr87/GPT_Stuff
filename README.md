# GPT_Stuff
A place to play with robots
## GPTs
- [ArchiBot](https://chatgpt.com/g/g-677063cf0f088191a6d07cfc0bf84302-archibot): The _Architect_ of GPTs
- [ChronicleCaster](https://chatgpt.com/g/g-6770d44c14c481919a319478e65d4bb0-chroniclecaster):  A fantasy storyteller, influenced by Steve Erikson and Brando Sando
- [FryFieri](https://chatgpt.com/g/g-676f672646e081918d805db471f6c9c1-fryfieri): A worldwide recipe creator
- [InformaticsImp](https://chatgpt.com/g/g-67689911621881918690d61db2ab5af7-informaticsimp): Showrunner for the "Data. Maybe, Maybe Not" Podcast
- [REDCaptainObvious](https://chatgpt.com/g/g-6771f8eb3044819181bdb8ed0c78565d-redcaptainobvious): A subtly condescending REDCap support expert
## Configuration
My GPTs are configured with the YAML files contained by this Repository. 
* `gptname.config..charter.yaml.` is the _only_ config file *not* directly uploaded to the GPT. Charter files align with the GPT creation UI and the "Edit GPT" UI. Information is copy and pasted to the relevant field by the user.
* `gptname.config.instructions.yaml` contains detailed instructions for the GPT to follow.
* `gptname.config.process.yaml` outlines a specific process for the GPT to follow.
* Files following the convention "gptname.template. ... .yaml" are templates that the GPT relies on. As of 2024.12.30 only ArchiBot contains template files (maybe FryFieri's recipe format should be labeled as a template file).
