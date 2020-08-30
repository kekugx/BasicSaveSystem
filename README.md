# BasicSaveSystem
How To Use

Implementation:
1-) Add SaveManager.cs to any of gameobject in your scene.
2-) Update save path value if SaveManager.cs (Optional)
3-) Edit Save.cs file which datum you want to save.

How To:
- SaveManager.Instance.Load(); // Load data from save path.
- SaveManager.Instance.Save(save); // You can use this line for saving


Save Example:

 var save = SaveManager.Instance.Load();
 
 save.CurrentLevel++;
 
 SaveManager.Instance.Save(save); //Save method 1
 save.Save(); //Save method 2
