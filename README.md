# TUGAS-UAS-MATEMATIKA-DISKRIT
Laporan Program Tree Traversal dan Graph Traversal
Pendahuluan
Program ini dibuat untuk memahami konsep struktur data Tree dan Graph serta cara penelusurannya menggunakan bahasa pemrograman Python. Program ini mengimplementasikan traversal pada Binary Tree serta algoritma DFS dan BFS pada Graph.
Tujuan Program
Tujuan dari pembuatan program ini adalah:
1. Memahami konsep Binary Tree dan Graph.
2. Mengimplementasikan traversal Preorder, Inorder, dan Postorder.
3. Memahami perbedaan algoritma DFS dan BFS.
4. Menerapkan konsep struktur data dalam pemrograman Python.
Struktur Program
Struktur program dibagi menjadi beberapa bagian utama, yaitu:
1. Identitas Program
2. Class Node sebagai struktur Binary Tree
3. Fungsi Traversal Tree
4. Representasi Graph
5. Algoritma DFS dan BFS
Identitas Program
Bagian ini digunakan untuk menampilkan identitas mahasiswa berupa nama, NIM, dan kelas. Tujuannya adalah sebagai informasi awal saat program dijalankan.
Class Node (Binary Tree)
Class Node berfungsi untuk membentuk struktur Binary Tree. Setiap node memiliki data, anak kiri, dan anak kanan. Class ini menjadi dasar dalam pembuatan tree.
Pembuatan Struktur Binary Tree
Struktur Binary Tree dibuat secara manual dengan satu node sebagai root dan beberapa node sebagai anak kiri dan kanan untuk membentuk hierarki tree.
Traversal Binary Tree
Traversal digunakan untuk mengunjungi seluruh node dalam tree.

Preorder Traversal: Mengunjungi node dengan urutan Root, Left, Right.
Inorder Traversal: Mengunjungi node dengan urutan Left, Root, Right.
Postorder Traversal: Mengunjungi node dengan urutan Left, Right, Root.
Representasi Graph
Graph direpresentasikan menggunakan adjacency list dalam bentuk dictionary. Setiap node memiliki daftar node yang saling terhubung.
DFS (Depth First Search)
DFS menelusuri graph secara mendalam terlebih dahulu menggunakan rekursi. Algoritma ini cocok untuk pencarian jalur tertentu.
BFS (Breadth First Search)
BFS menelusuri graph berdasarkan level menggunakan queue. Algoritma ini cocok untuk pencarian jarak terpendek pada graph tidak berbobot.
Kesimpulan
Program ini menunjukkan bagaimana struktur data Tree dan Graph dapat diimplementasikan menggunakan Python. Setiap metode traversal memiliki tujuan dan karakteristik yang berbeda.
