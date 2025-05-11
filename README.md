public class GithubProfileGenerator {

    public static void main(String[] args) {
        String githubImage = "<div align=\"center\">\n" +
                "  <img src=\"git_image.png\" alt=\"Gonn's Github\" width=\"300\">\n" +
                "</div>\n\n<br>\n\n";

        String techStack = "<div align=\"center\">\n" +
                "  <h2>✨ Tech Stack ✨</h2>\n" +
                "  <img src=\"https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white\" alt=\"Java\">\n" +
                "  <img src=\"https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white\" alt=\"Spring\">\n" +
                "  <img src=\"https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=android-studio&logoColor=white\" alt=\"Android Studio\">\n" +
                "  <br>\n" +
                "  <img src=\"https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white\" alt=\"HTML5\">\n" +
                "  <img src=\"https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white\" alt=\"CSS3\">\n" +
                "  <img src=\"https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black\" alt=\"JavaScript\">\n" +
                "  <img src=\"https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white\" alt=\"Figma\">\n" +
                "  <img src=\"https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobe-photoshop&logoColor=white\" alt=\"Photoshop\">\n" +
                "</div>\n\n<br><br>\n\n";

        String tools = "<div align=\"center\">\n" +
                "  <h2>🛠 Tools 🛠</h2>\n" +
                "  <img src=\"https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white\" alt=\"Git\">\n" +
                "  <img src=\"https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white\" alt=\"GitHub\">\n" +
                "  <br>\n" +
                "  <img src=\"https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white\" alt=\"MySQL\">\n" +
                "  <img src=\"https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white\" alt=\"MongoDB\">\n" +
                "  <img src=\"https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white\" alt=\"VSCode\">\n" +
                "</div>\n\n<br><br>\n\n";

        String contact = "<div align=\"center\">\n" +
                "  <h2>📫 Contact 📫</h2>\n" +
                "  <a href=\"mailto:gounpark7475@gmail.com\">\n" +
                "    <img src=\"https://img.shields.io/badge/gounpark7475@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white\" alt=\"Gmail\">\n" +
                "  </a>\n" +
                "</div>\nzhemdhfb";

        String readmeContent = githubImage + techStack + tools + contact;

        System.out.println(readmeContent);
    }
}
