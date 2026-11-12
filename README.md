# flowchart-memeriksa-payungflowchart-memeriksa-payung
Flowchart memeriksa payung sebelum berangkat sekolah atau kerja
flowchart TD
    A([Mulai]) --> B[Memeriksa kondisi cuaca]
    B --> C{Apakah hujan?}
    C -- Ya --> D[Ambil payung]
    C -- Tidak --> E{Apakah langit mendung?}
    E -- Ya --> D
    E -- Tidak --> F[Berangkat tanpa payung]
    D --> G[Memastikan payung berfungsi]
    G --> H[Membawa payung]
    H --> I([Berangkat ke sekolah atau kerja])
    F --> I
