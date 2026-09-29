# Demo: ιστότοπος και πάνελ ψυχολόγου (Θεσσαλονίκη)

Διαδραστικό πρωτότυπο με ψεύτικα δεδομένα, στα ελληνικά. Στατικό site, χωρίς build.

- `index.html`: δημόσιος ιστότοπος (κράτηση ραντεβού, blog, επικοινωνία, πύλη πελάτη)
- `admin.html`: πάνελ διαχείρισης (είσοδος: οποιοδήποτε email και κωδικός 6+ χαρακτήρων, 2FA: `123456`)
- `design-system/`: tokens, οδηγίες ύφους, κάρτες συστατικών και `TECHNICAL-NOTES.md` (τεχνικές παραδοχές, στα αγγλικά)
- `vercel.json`: noindex headers

Τα στοιχεία επικοινωνίας, ο αριθμός άδειας και οι γραμμές βοήθειας είναι ενδεικτικά.

## Deploy στο Vercel
Vercel → Add New → Project → Import από αυτό το GitHub repo. Framework Preset: Other, χωρίς build command. Κάθε push στο `main` κάνει αυτόματα νέο deploy.
