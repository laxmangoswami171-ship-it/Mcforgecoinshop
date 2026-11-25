# MCForgeCoinShop Starter

GitHub Actions automatic build is included (Java 17 + Maven).

## Build on GitHub from phone
1. Create a GitHub repository.
2. Upload/unzip these project files into the repository root (keep `.github/workflows/build.yml`).
3. Commit to `main`.
4. Open repository -> **Actions** -> **Build MCForgeCoinShop**.
5. Wait for green successful build.
6. Open completed workflow -> **Artifacts** -> download `MCForgeCoinShop-JAR`.

## Local build
Requires JDK 17+ and Maven: `mvn clean package`

Output: `target/MCForgeCoinShop-1.0.0.jar`

This remains a starter plugin; full admin GUI editor, tag ownership/equip, chat/TAB formatting, and plugin-specific integrations are not yet implemented. API/version compatibility is not verified beyond targeting Paper 1.21.4.
