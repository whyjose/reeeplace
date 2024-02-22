import os

def rename_files(folder_path):
    for filename in os.listdir(folder_path):
        if "KEYWORD" in filename:
            new_filename = filename.replace("KEYWORD", "NEWKEYWORD")
            os.rename(os.path.join(folder_path, filename), os.path.join(folder_path, new_filename))
            print(f"Renamed: {filename} -> {new_filename}")

if __name__ == "__main__":
    folder_path = input("Enter the folder path: ")
    rename_files(folder_path)
