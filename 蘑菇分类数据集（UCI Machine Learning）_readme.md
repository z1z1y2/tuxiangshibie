---
Field:
    - 机器学习/分类

Ext:
    - .csv

DatasetUsage:
    - 374003
---

## **背景介绍**

数据集中包含了8124个样本和22个变量（如蘑菇的颜色、形状、光滑度等）。每一种都被分为绝对可食用的，绝对有毒的，或者具有未知的可食性。该数据集是探究机器学习分类算法算法不可多得的一个优质数据集。

> **通过以上数据集我们也提出了三个值得探索的问题：**
> * 基本的数据可视化
> *  什么类型的机器学习模型在该数据集中表现最好？
> * 哪些是最有效区分毒蘑菇的特征？


## **数据字典**

**cap-shape: **bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s
**cap-surface:** fibrous=f,grooves=g,scaly=y,smooth=s
**cap-color: **brown=n,buff=b,cinnamon=c,gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y
**bruises: **bruises=t,no=f
**odor: **almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s
**gill-attachment:** attached=a,descending=d,free=f,notched=n
**gill-spacing: **close=c,crowded=w,distant=d
**gill-size: **broad=b,narrow=n
**gill-color:** black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y
**stalk-shape: **enlarging=e,tapering=t
**stalk-root:** bulbous=b,club=c,cup=u,equal=e,rhizomorphs=z,rooted=r,missing=?
**stalk-surface-above-ring:** fibrous=f,scaly=y,silky=k,smooth=s
**stalk-surface-below-ring: **fibrous=f,scaly=y,silky=k,smooth=s
**stalk-color-above-ring: **brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
**stalk-color-below-ring: **brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y
**veil-type: **partial=p,universal=u
**veil-color: **brown=n,orange=o,white=w,yellow=y
**ring-number: **none=n,one=o,two=t
**ring-type:** cobwebby=c,evanescent=e,flaring=f,large=l,none=n,pendant=p,sheathing=s,zone=z
**spore-print-color: **black=k,brown=n,buff=b,chocolate=h,green=r,orange=o,purple=u,white=w,yellow=y
**population:** abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y
**habitat: **grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d

## **引用格式**
```
@misc{Mushroom,
    title = { 蘑菇分类数据集（UCI Machine Learning） },
    author = { 方小鲸 },
    howpublished = { \url{https://www.heywhale.com/mw/dataset/5a4c87653616537d65c7cdcc} },
    year = { 2018 },
}
```