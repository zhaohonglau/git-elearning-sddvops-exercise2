# Instruction
1) Clone this repository using Eclipse IDE
2) In Eclipse IDE, perform the following:
      - **Create a new branch** called new-feature-branch from main
      - **In new-feature-branch** add "Bruce Lee" to a new line in files/staff.txt. Commit that change with the message "Added Bruce Lee"
      - **Switch back to the main branch** add a new file called files/employer.txt containing "RP". Commit this file with the message "Add employer file"
      - Merge all changes from the main branch into the new-feature-branch branch and vice versa

3) After you have successfully merged the branches, perform the following:
      - **Create a new branch** called new-feature-branch2
      - **In new-feature-branch2** add "Andy Lau" to a new line in files/staff.txt. Commit that change with the message "Added Andy Lau"
      - **Switch back to main branch** add "Jacky Chan" to a new line in files/staff.txt. Commit that change with the message "Added Jacky Chan"
      - **Attempt to merge all changes** from new-feature-branch2 into the main branch
      - **Resolve conflicts** by Adding both Andy Lau and Jacky Chan into the staff.txt file

3) Download [gitruler.jar](https://github.com/rcraggs/gitruler/releases/download/V1.2.5/gitruler.jar) file
4) Use the command **java -jar [path-to-gitruler.jar] -c [path-to-gitrules.json] -r [path-to-local-repo]**
      
e.g. java -jar ./gitruler.jar -c ./gitrules.json -r ./git-elearning-sddvops-exercise1
