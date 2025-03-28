# MyChess Game Website
♟️ **Play chess in real-time with friends across devices!**

---

## 🚀 **About**
MyChess is an interactive, two-player chess game that brings the classic board game to life with modern features. Play against a friend in real-time, whether on a mobile, tablet, or desktop, and enjoy a seamless, engaging experience complete with chat and intuitive gameplay.

---

## 🕹️ **Features**
- **Multi-Device Compatibility**  
  Enjoy chess on any device—mobile, tablet, or desktop—with a responsive design that adapts to your screen for a smooth experience.

- **Drag-and-Drop Functionality**  
  Move pieces effortlessly with intuitive drag-and-drop controls—no complicated inputs required.  
  ![Drag-and-Drop Functionality](https://nikhil-nagar.vercel.app/assets/1-CoE2o3Ic.jpeg)

- **Real-Time Updates**  
  Experience fluid gameplay with dynamic, real-time board updates as moves are made.

- **Pop-Up Notifications**  
  Stay informed with instant alerts for key game moments:  
  - 🏆 **Checkmate! You win!**  
  - ❌ **Checkmate! You lose!**  
  - 🤝 **Stalemate! The game is a draw.**  
  - ⚠️ **The king is in check!**  
  ![Checkmate Notification](https://nikhil-nagar.vercel.app/assets/2-Bc4sbdkj.jpeg)

- **Real-Time Chat Feature**  
  Chat with your opponent during the game—share strategies, banter, or just catch up!  
  ![Real-Time Chat](https://nikhil-nagar.vercel.app/assets/4-C1ZS7rlu.webp)

---

## 🧠 **Chess.js Integration**
MyChess leverages [Chess.js](https://github.com/jhlywa/chess.js) to manage all chess logic, ensuring a reliable and rule-compliant game.

- **Key Functionalities**:  
  - Tracks the game state, including board setup and piece positions.  
  - Validates moves to enforce legality (e.g., bishops can’t jump pieces).  
  - Detects game-ending conditions like checkmate or stalemate.  

- **Why Chess.js?**  
  By handling the complex rules of chess, Chess.js lets us focus on building a sleek user interface and real-time features.

---

## 🔌 **Socket.io for Real-Time Moves and Chat**
Socket.io powers the real-time magic of MyChess, enabling instant move updates and live chat between players.

- **Chess Move Transfer**:  
  - A player’s move is sent to the server via Socket.io.  
  - The server instantly broadcasts it to the opponent, updating their board.  

- **Chat System**:  
  - Send and receive messages in real-time during the game, all powered by Socket.io.  

- **Benefits**:  
  - Ensures smooth, lag-free gameplay and communication across devices.

---

## 📸 **Screenshots**
See MyChess in action:  

- **Drag-and-Drop Gameplay**  
  ![Drag-and-Drop](https://nikhil-nagar.vercel.app/assets/1-CoE2o3Ic.jpeg)  

- **Checkmate Alert**  
  ![Checkmate](https://nikhil-nagar.vercel.app/assets/2-Bc4sbdkj.jpeg)  

- **Real-Time Chat**  
  ![Chat](https://nikhil-nagar.vercel.app/assets/4-C1ZS7rlu.webp)  

---

## 🛠️ **How to Play**
1. **Visit the Website**  
   Head to [MyChess Website](https://yourwebsite.com) on any device.  

2. **Start or Join a Game**  
   - Create a new game and share the unique game ID with your friend.  
   - Or, enter an existing game ID to join.  

3. **Play and Chat**  
   - Drag and drop pieces to make moves.  
   - Use the chat feature to talk with your opponent in real-time.  

---

## 🤝 **Contributing**
Want to make MyChess even better? Here’s how:  
1. Fork the repository.  
2. Create a new branch (`git checkout -b feature-branch`).  
3. Commit your changes (`git commit -m "Add feature"`).  
4. Push to the branch (`git push origin feature-branch`).  
5. Submit a pull request.  

---

## 📄 **License**
This project is licensed under the MIT License—see the [LICENSE](LICENSE) file for details.

---

## 📧 **Contact**
- **Nikhil Nagar**  
- Email: nsquarepart1@gmail.com  
- GitHub: [nikhilnagar29](https://github.com/nikhilnagar29)  

---

**Ready to challenge your friends? Play MyChess today!** ♟️