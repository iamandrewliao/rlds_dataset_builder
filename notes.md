# create customer dataset
0. conda activate rlds_env
1. copy example_dataset and rename
2. change the name of example_dataset_dataset_builder.py
3. change the class name ExampleDataset
4. cd example_dataset
5. transfer dataset and rename or soft link 
    (ln -s /data/cui00191/real_world_data/pick_green_into_bowl /home/cui00191/projects/rlds_dataset_builder/pick_green_into_bowl/data)
6. tfds build --overwrite


# Todo
1. fix visualization bug