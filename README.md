# May Madness Predictions

Our [May Madness Predictions](./docs/index.md) aggregate several different metrics for each match played in the NCAA Men's and Women's Division I Tennis Championships. This is the GitHub repository used to host the site. You can switch to the [GitHub May Madness](https://slam10s.github.io/may-madness/) website by clicking [here](https://slam10s.github.io/may-madness/).

## Watch Live

If you want follow the matches, the best resource online is at [Bobby Knight](https://twitter.com/College10s2day)'s [College Tennis Today](https://www.collegetennistoday.com/) website. He has a [2021 NCAA Championships](https://www.collegetennistoday.com/2021-ncaa-championships/) page with links to brackets and a schedule for the upcoming matches with the Live Scoring and Video links for each match.

## The Predictions

You can find a complete listing of the predictions for each match here:

- [2021 NCAA Men's Championships](./docs/2020-21/ncaam/index.md)
- [2021 NCAA Women's Championships](./docs/2020-21/ncaaw/index.md)

## Tournament Schedule

Here's daily listings of the matches by start time:

- [Saturday, May 8](./2020-21/schedule/05-08.md)
- [Friday, May 7](./2020-21/schedule/05-07.md)

## The Metrics

We're not pushing any particular metrics on you. All the different metrics have their own strengths and weaknesses. We just aggregate the different ones and let you decide which one(s) you like.

### SLAM.Tennis Ratings

The [SLAM.Tennis](https://www.slam.tennis/teams/rankings.asp) power ratings are the ratings we use to submit votes each week for the [Tennis Channel/USTA Top 25](https://www.usta.com/en/home/play/college-tennis/programs/national/top-25.html). The algorithm is a weighted variant of the [Bradley-Tenny Model](https://en.wikipedia.org/wiki/Bradley%E2%80%93Terry_model).

### Tennis Recruiting Network (TRN) Ratings

The [TRN Algorithm](https://tennisrecruiting.net/article.asp?id=2499) is the same algorithm we use to generate the [College Recruiting Lists](https://tennisrecruiting.net/Boys.asp) at the Tennis Recruiting Network. It is a vinalla implementation of the [Bradley-Tenny Model](https://en.wikipedia.org/wiki/Bradley%E2%80%93Terry_model) that does not use scores or time-decay.

### The Massey Ratings

The [Massey Ratings](https://www.masseyratings.com/) are the gold standard for computer ratings done for virtually every sport. Kenneth Massey produces his metrics for:

- [College Men's Teams](https://www.masseyratings.com/ctm/ratings)
- [College Women's Teams](https://www.masseyratings.com/ctw/ratings)
- [College Men's Singles](https://www.masseyratings.com/ctms/ratings)
- [College Women's Singles](https://www.masseyratings.com/ctws/ratings)

### Lineup Ratings

Some teams just don't match up against other teams the way you might think depending on the lineups. We compute expected win percentages based on a composite metric for each individual match.

### Universal Tennis Ratings

The [Universal Tennis Ratings](https://www.myutr.com/) are the gold standard for tennis ratings known by any serious tennis player. We use both the [Power 6](https://app.myutr.com/search?type=colleges&utrFitPosition=6&utrMax=16&utrMin=1&utrTeamType=singles&utrType=verified) in team comparisons and individual's verified [Singles Rating](https://support.myutr.com/en/support/solutions/articles/9000151830-understanding-the-algorithm-complete-summary) for player comparisons.

### Composite Metrics

Don't like one algorithm? Well how about a composite? Our Composite metric averages the expected win percentages for the different algorithms with probabilistic ratings.

### Intercollegiate Tennis Association

The [ITA Point System](https://www.wearecollegetennis.com/ita-rankings/rankings-explained/) is the system used by the NCAA uses for seeding and selection into the NCAA Tennis Championships. These are _the_ rankings people use when referring to players and teams in college tennis.

### USTA Top 25 Poll

The USTA and Tennis Channel have partnered to celebrate the best 25 NCAA Division I men's and women's programs each week during the spring season. The voting panel consists of experts from around the country, including media members and former coaches. The [Tennis Channel/USTA Top 25](https://www.usta.com/en/home/play/college-tennis/programs/national/top-25.html) rankings are announced every Wednesday at approximately 10 a.m. ET on the USTA social media channels and USTA.com.

### ITA Coaches Poll

The ITA Coaches Poll is a similar poll produced by the ITA each week alongside the computer rankings.

## License

All data and files in this repository are licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

Attribution is required. Non-commercial use only.
