# _var.scss---Globaly-variable-scss...
/*Globaly SACC Variable*/ 

// Border Radius 

$default-border-radius: 5px;  
@mixin border-radius($radius) {   
-webkit-border-radius: $radius;      
-moz-border-radius: $radius;       
-ms-border-radius: $radius;           
border-radius: $radius; }  

// Transition 
$default-transition-property: all; 
$default-transition-duration: 200ms; 
$default-transition-function: linear; 
$default-transition-delay: 0;   
// Primary Break Points 
// These should be used with the bp (max-width, xx) mixin 
$bp-xsmall: 479px; 
$bp-small: 599px; 
$bp-medium: 770px; 
$bp-large: 979px; 
$bp-xlarge: 1199px;  
// Base Values Spacing 
$gap: 10px; 
$trim: 30px;  
// This will get applied on viewports smaller than 480px 
$trim-small: 15px;  
// Padding that will get applied to content areas 
$box-spacing-large: 20px;  
// Standard padding around box elements such as banner messages, etc 
$box-spacing: 10px;  

// Standard spacing between elements within a box, such as "Add to cart", "Price box", etc 
$element-spacing: 7px;  
// Dimensions 
$max-content-width: 1200px; 
$max-container-width: $trim + $max-content-width + $trim; $max-std-formatted-width: 50em;  
// Brand Colors Background 
$c-blue: #3399CC; 
$c-green: #11B400; 
$c-pink: #D85378; 
$c-orange: #F3793B; 
$c-red: #CF5050; 
$c-yellow: #FFDD15; 
$c-black: #000000;  

// Base Colors Text 
$c-text: #636363; 
$c-text-gray: #A0A0A0; 
$c-text-white: #E6E6E6;  // Primary font color for headings and other non-link text $c-text-primary: $c-blue;  // Interaction $c-action: $c-blue; $c-stimulus: darken($c-blue, 15%); $c-subtle: #A0A0A0;  // Notifications Message $c-danger: #FF0000; $c-success: $c-green; $c-warn: #E26703; $c-dark: #676157;  // Global Elements $c-divider-border: #ECECEC;  // Element colors Button $c-button: $c-blue; $c-button-hover: darken($c-blue, 5%); $c-button-active: darken($c-blue, 10%);  // Secondary Buttons $c-button-secondary: #DDDDDD; $c-button-secondary-hover: darken(#DDDDDD, 5%); $c-button-secondary-active: darken(#DDDDDD, 10%); $c-button-subtle: #ECECEC;  // Forms $c-input-border: #C0C0C0; $c-input-border-focus: $c-blue;  $c-input-placeholder: $c-text-gray; $c-input-text: $c-text;  $c-fieldset-border: #CCCCCC; $c-fieldset-border-light: #EDEDED;  // Headings $c-h1: $c-blue; $c-h2: $c-text; $c-h3: $c-text; $c-h4: $c-text; $c-h5: $c-text; $c-h6: $c-text;  // Link $c-link: $c-action; $c-link-hover: darken($c-action, 5%); $c-link-focus: $c-action; $c-link-active: darken($c-action, (5% / 2));  // Module (generic) $c-module-background: #F4F4F4;  // This should be applied whenever the border is surrounding a white element and/or is directly showing on white. $c-module-border: #CCCCCC;  // This should be applied whenever the border is wrapping an element with $c-module-background $c-module-border-light: #EDEDED; $c-module-border-highlight: $c-blue;  // Table $c-table-background: #F4F4F4; $c-table-border: #C0C0C0;  $c-table-zebra-odd: #F8F7F5; $c-table-zebra-even: #EEEDED;  // Tabs $c-tabs-background: #F0F0F0;   // Typography // Google Web Font stylesheet is included via layout XML  // Font Stacks $f-stack-sans: 'Helvetica Neue', Verdana, Arial, sans-serif; $f-stack-serif: Georgia, Times, 'Times New Roman', serif; $f-stack-special: 'Raleway', 'Helvetica Neue', Verdana, Arial, sans-serif; $f-stack-default: $f-stack-sans;  // Font Sizes $f-size-xxl: 18px; $f-size-xl: 16px; $f-size-l: 15px;  $f-size: 14px;  $f-size-s: 13px; $f-size-xs: 12px; $f-size-xxs: 11px;  // Base Measures $b-line-height: 1.5; $b-margin-bottom: 1.5em;
