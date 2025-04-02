# AI Music Sampler

An AI-powered web application for generating and sampling music from any genre and era.

## Features

- Generate AI music samples based on genre and era inputs
- Interactive audio player with visualizer
- Playback controls (play/pause, next/previous)
- Adjustable volume and tempo
- Responsive design for desktop and mobile

## Technologies Used

- Next.js 14 - React framework for web development
- TypeScript - For type safety and better developer experience
- Tone.js - Audio framework for music creation and manipulation
- Tailwind CSS - For styling and responsive design
- OpenAI API integration (mock implementation)

## Getting Started

### Prerequisites

- Node.js 18 or later
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/aimusic-sampler.git
   cd aimusic-sampler
   ```

2. Install dependencies:
   ```
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to https://

## Usage

1. Enter a music genre (e.g., Jazz, Hip Hop, Classical) in the Genre field
2. Enter a time period or era (e.g., 1970s, Renaissance, Modern) in the Era field
3. Click "Generate Samples" to create AI-generated music samples
4. Use the player controls to listen to and adjust the generated samples
5. Adjust volume and tempo using the sliders

## Future Enhancements

- Integration with actual AI music generation models
- Ability to save and share generated samples
- More audio effects and manipulation tools
- User accounts and saved sample libraries
- Export options for different audio formats

## Project Structure

```
aimusic-sampler/
├── public/
│   └── samples/    # Sample audio files
├── src/
│   ├── app/        # Next.js app router components
│   ├── components/ # Reusable React components
│   ├── lib/        # Utility functions and API calls
│   └── types/      # TypeScript type definitions
├── .eslintrc.json  # ESLint configuration
├── next.config.js  # Next.js configuration
├── package.json    # Project dependencies
├── postcss.config.js # PostCSS configuration
├── tailwind.config.js # Tailwind CSS configuration
└── tsconfig.json   # TypeScript configuration
```

## License

This project is licensed under the ISC License - see the LICENSE file for details.

## Acknowledgments

- [Tone.js](https://tonejs.github.io/) for the audio processing capabilities
- [OpenAI](https://openai.com/) for AI technologies inspiration 