# TUGAS_STI
program biodata;

{ Deklarasi variabel }
var
  npm: string;
  jurusan: string;
  tempat: string;
  tanggal_lahir: string;

begin
  { Input data }
  write('Masukkan NPM: ');
  readln(npm);
  write('Masukkan jurusan: ');
  readln(jurusan);
  write('Masukkan tempat lahir: ');
  readln(tempat);
  write('Masukkan tanggal lahir (dd/mm/yyyy): ');
  readln(tanggal_lahir);

  { Tampilkan biodata }
  writeln('Biodata:');
  writeln('NPM: ', npm);
  writeln('Jurusan: ', jurusan);
  writeln('Tempat lahir: ', tempat);
  writeln('Tanggal lahir: ', tanggal_lahir);
end.
