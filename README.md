# Russia Ukraine Weibo Crisis (RUW) Dataset


Download link is [here](https://uofi.box.com/s/qn99omy53muyi9a4z72s4qktx3h3gzvz).

### Motivation
Online social networks such as Twitter and Weibo play an important role in how people stay informed and exchange reactions. In particular, online social networks during crisis events embody a key opportunity for studying the portability of computational models for various tasks (e.g., information extraction, complex event understanding, misinformation detection, etc.), due to differences in domain, entities, and event types. We present the **Russia-Ukraine Crisis Weibo (RUW) dataset**, with over 3.5M user posts and comments in our first release.

### Dataset Details
We initiated our data collection process on the last week of Feb, 2022 when the crisis escalated with Russia's special military operation. The following information are included in the *Russia-Ukraine Crisis Weibo (RUW) dataset*:
|      |  |
| ----------- | ----------- |
| user information     | profile ID, profile name, profile image, and profile description       |
| post content  | the main text, as well as any images and videos attached, if available      |
| post metdata  | the \# of likes and shares on the post      |
| post comments | information similar to the previous three rows, for all comments underneath a user post      |

We are continueing the data collection process to follow the latest development of events in the ongoing crisis, and will update our dataset daily. 

### Use Cases
There are many interesting task settings that can be experimented with, using our Russo-Ukranian Crises Weibo dataset. These include event clustering, false rumor detection, and portability of news analytic methodologies across Twitter and Weibo domains. 

### Related Work
A team at HKUST has released a Twitter dataset on the Russo-Ukranian Crises.

## References
If you found our dataset and work helpful, please cite:
```
@misc{fung22ruw,
  title={A Weibo Dataset for the 2022 Russo-Ukrainian Crisis},
  author={Fung, Yi and Ji, Heng},
  booktitle={Arxiv},
  pages={01--02},
  year={2022}
}
```
