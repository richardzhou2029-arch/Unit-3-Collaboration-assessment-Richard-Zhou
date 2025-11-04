Welcome to **TreeLife**, your guide to learning about the beauty, diversity, and importance of trees around the world.

---

## About Us

At **TreeLife**, we're passionate about forests and green living.

Our mission is to:
- Educate people about the different types of trees.
- Promote sustainable forestry.
- Encourage reforestation projects.

"The best time to plant a tree was 20 years ago. The second best time is now."
- *Chinese Proverb*

---

## Featured Trees

**Oak Tree**
**Scientific name**: *Quercus robur*
Known for its strength and longevity, the oak is a symbol of endurance.
![Oak tree](https://images.squarespace-cdn.com/content/v1/5cb3ca007a1fbd45aeff89ea/116e839c-0a24-4f22-91c1-55bb7e44b427/nashville-tree-conservation-corps-how-many-oak-tree-types-tn.jpg)

---

**Pine tree**
**Scientific name**: *Pinus*

Evergreen and aromatic, pine trees thrive in colder regions.
![Pine tree](https://gardenerspath.com/wp-content/uploads/2023/08/Pine-Tree-Propagation-Feature.jpg)

## Tree Identification Tool

You can use this simple **Javascript** function to identify a tree by its charcteristics.

```

function identify_tree(leaf_shape, region){
    if (leaf_shape == "needle" && region == "cold"){
        return "Pine Tree"
    } else if (leaf_shape == "broad" && region == "temperature"){
        return "Oak Tree"
    } else {
        return "Unknown Tree"
    } 
}
console.log(identify_tree("needle", "cold"))

```