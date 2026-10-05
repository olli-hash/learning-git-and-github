### Tag 1

- 55min Tutorial zu Branching, das Remote Repositories vorerst außen vor lässt:
[Git Branching and Merging - Detailed Tutorial](https://www.youtube.com/watch?v=Q1kHG842HoI)
```
git branch feature1
git checkout feature1
# some commits ...
git log --all --graph
git checkout main
# some commits ...
git log --all --graph
```
- [11:30](https://youtu.be/Q1kHG842HoI?si=1o-AodZKQ9BuPOcg&t=690)
```
git checkout main    # Hier soll der neue merge-result-commit entstehen
git merge feature1
# Oder:
git merge feature1 -m "Merke Feature1"

```
- [19:22](https://youtu.be/Q1kHG842HoI?si=voVGTJo8UnpVyMIC&t=1162)



