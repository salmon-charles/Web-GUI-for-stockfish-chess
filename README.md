Web GUI for stockfish chess
===========================
Demo:
[http://netreal.de/bot-chess/](http://netreal.de/bot-chess/)

It is based on: chessboard.js<br />
https://github.com/oakmac/chessboardjs<br />
1) Install stockfish<br />
https://stockfishchess.org/<br />
sudo apt-get install git g++<br />
git clone https://github.com/mcostalba/Stockfish.git<br />
cd Stockfish/src<br />
make help<br />
make profile-build ARCH=x86-64<br />
make profile-build ARCH=x86-32<br />
./stockfish<br />
go infinite<br />

2) git clone https://github.com/antiproton/Web-GUI-for-stockfish-chess.git<br />
Edit config.php<br />
That is all! Enjoy it