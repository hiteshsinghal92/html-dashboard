# Dashboard UI

This project is a simple, responsive dashboard layout built using only HTML and CSS. The dashboard includes a sidebar, top bar, widgets section, and a table with a search bar. The layout is designed to be responsive, with a focus on a minimum screen width of 1200px.

## Features

- **Responsive Design**: The layout adjusts according to the screen width, ensuring a good user experience on different screen sizes.
- **Sidebar Navigation**: A vertical sidebar containing navigation links and a logo.
- **Top Bar**: Contains the dashboard name and buttons for quick actions.
- **Widgets Section**: Displays key metrics in a grid layout.
- **Table with Search**: A table with a title and search box for filtering data.

## How to Use

1. **Download and Run**:
   - Download or clone the repository to your local machine.
   - Open `index.html` in your preferred web browser.

2. **Customizing for 1200px Screen Width**:
   - The layout is designed to be responsive, but you can customize the appearance for screens with a width of 1200px or less.
   - In the `styles.css` file, you'll find certain sections of code that are commented out. These sections can be uncommented based on your specific requirements.

   For example:

   ```css
   /* Uncomment the following code if you want to hide the sidebar on screens less than 1200px wide */
   /*
   @media (max-width: 1200px) {
        .top-bar {
        flex-direction: column;
        align-items: flex-start;
    } 
    
    .top-bar .buttons {
        margin-top: 0.5rem;
    }

     .widgets-section {
        grid-template-columns: 1fr;
    } 
   }
   */
