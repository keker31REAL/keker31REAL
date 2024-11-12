

def brute_force(charset, length, prefix=""):
    if length == 0:
        print(prefix)
        return
    for char in charset:
        brute_force(charset, length - 1, prefix + char)

charset = string.ascii_lowercase + string.digits  # Lettres et chiffres
length = 4  # Longueur du mot de passe
brute_force(charset, length)

<!---
keker31REAL/keker31REAL is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
