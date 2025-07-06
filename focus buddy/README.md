
# Focus Buddy 🐱

A gamified time management app that helps you stay focused and productive while taking care of virtual pets!

## 🌟 Features

### 🎯 Focus Timer
- Customizable session lengths (15, 25, 30, 45, 60, 90 minutes)
- Visual progress circle with real-time updates
- Task-specific XP multipliers
- Streak tracking for consistent productivity

### 🐾 Virtual Pets
- **5 Different Pets**: Cat, Dog, Rabbit, Bird, Fish
- **Evolution System**: Pets evolve as they level up
- **Care System**: Feed and play with your pets using XP
- **Mood System**: Pets show different emotions based on happiness
- **Unlock System**: Earn XP to unlock new pets

### 🏆 Gamification
- **XP System**: Earn experience points for completed sessions
- **Level Progression**: Pets level up based on total XP
- **Streak Bonuses**: Maintain streaks for bonus XP
- **Task Multipliers**: Different activities give different XP rewards

### 🎨 Beautiful UI/UX
- **Modern Design**: Clean, intuitive interface
- **Responsive Layout**: Works on all device sizes
- **Smooth Animations**: Engaging visual feedback
- **Accessibility**: Keyboard navigation and focus states

## 📁 Project Structure

```
focus-buddy/
├── index.html          # Main HTML file (root)
├── public/
│   └── index.html     # Alternative HTML file for deployment
├── package.json        # Project configuration
├── _redirects          # Routing configuration
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Simple Setup
1. **Clone or Download** the project files
2. **Open `index.html`** directly in your web browser
3. **Start Focusing!** Choose your pet and begin your productivity journey

### For Vercel Deployment
The app is ready for Vercel deployment! Simply:
1. **Push to GitHub**
2. **Connect to Vercel**
3. **Deploy automatically**

## 🎮 How to Play

### Starting a Session
1. **Choose Your Pet**: Select from available pets (start with Whiskers the cat)
2. **Pick Your Task**: Select what you'll be working on (Study, Work, Creative, etc.)
3. **Set Session Length**: Choose how long you want to focus (15-90 minutes)
4. **Start Timer**: Click the play button to begin your focus session

### Earning XP
- **Complete Sessions**: Finish focus sessions to earn XP
- **Task Multipliers**: Different tasks give different XP rewards
- **Streak Bonuses**: Maintain daily streaks for bonus XP
- **Pet Care**: Use XP to feed and play with your pets

### Pet Care
- **Feeding**: Costs 10 XP, increases hunger by 20% and happiness by 10%
- **Playing**: Costs 15 XP, increases happiness by 25%
- **Evolution**: Pets evolve at different levels with new appearances
- **Unlocking**: Earn XP to unlock new pet types

## 🛠️ Technical Details

### Built With
- **React 18**: Modern React with hooks
- **Tailwind CSS**: Utility-first CSS framework
- **Babel**: JavaScript compiler for JSX
- **Single HTML File**: No build tools required

### Key Components
- **Header**: XP and streak display
- **PetSelection**: Choose and manage pets
- **TaskSelection**: Select focus activities
- **PetDisplay**: Pet status and care interface
- **Timer**: Focus session timer with progress
- **Stats**: Daily progress tracking

### State Management
- **useState**: Local component state
- **useEffect**: Side effects and timers
- **useRef**: Timer interval management

## 🎨 Customization

### Adding New Pets
Edit the `pets` state in `index.html`:
```javascript
const [pets, setPets] = useState({
    // Add new pets here
    newPet: { 
        name: 'PetName', 
        level: 1, 
        hunger: 50, 
        happiness: 70, 
        unlocked: false 
    }
});
```

### Adding New Tasks
Edit the `TASK_TYPES` constant in `index.html`:
```javascript
const TASK_TYPES = {
    // Add new tasks here
    newTask: { 
        name: 'Task Name', 
        icon: '🎯', 
        xpMultiplier: 1.0 
    }
};
```

### Styling
- **Custom CSS**: Add styles in the `<style>` section of `index.html`
- **Tailwind Classes**: Use utility classes for quick styling
- **Animations**: Pre-built animation classes available

## 🔧 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ❌ Internet Explorer (not supported)

## 📱 Mobile Support

The app is fully responsive and works great on:
- 📱 Smartphones
- 📱 Tablets
- 💻 Desktop computers

## 🚀 Vercel Deployment

This app is optimized for Vercel deployment:

1. **GitHub Integration**: Push your code to GitHub
2. **Vercel Setup**: Connect your GitHub repo to Vercel
3. **Automatic Deployment**: Vercel will automatically deploy your app
4. **Custom Domain**: Optionally add a custom domain

### Vercel Configuration
- **Framework Preset**: Other
- **Build Command**: Not needed (static HTML)
- **Output Directory**: Root directory
- **Install Command**: Not needed

## 🎯 Tips for Success

1. **Start Small**: Begin with 25-minute sessions
2. **Choose Wisely**: Pick tasks that match your energy level
3. **Take Breaks**: Use the reset feature between sessions
4. **Care for Pets**: Keep your pets happy for better performance
5. **Build Streaks**: Consistent daily use increases rewards

## 🤝 Contributing

Feel free to:
- 🐛 Report bugs
- 💡 Suggest new features
- 🎨 Improve the design
- 📝 Add documentation

## 📄 License

This project is open source and available under the MIT License.

---

**Happy Focusing! 🚀** 