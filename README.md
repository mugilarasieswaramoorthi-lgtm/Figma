# Ex09 Event Registration Web Application
# Date:08/10/2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
home page:
import React from "react";
import saveetha11 from "./saveetha-1-1.png";
import textOnAPath from "./text-on-a-path.svg";

export const Iphone = (): JSX.Element => {
  return (
    <div className="bg-[#60efff] overflow-hidden w-full min-w-[390px] min-h-[844px] relative">
      <img
        className="absolute top-[177px] left-[79px] w-[217px] h-[209px] aspect-[1.04] object-cover"
        alt="Saveetha Engineering College Logo"
        src={saveetha11}
      />

      <div className="absolute top-[501px] left-[49px] w-[291px] h-[59px] bg-[#ff7e7e]" />

      <div className="absolute top-[519px] left-[103px] w-[211px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        TECH FEST-2025
      </div>

      <img
        className="absolute top-[503px] left-[-47px] w-[201px] h-[49px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <div className="absolute top-[625px] left-[106px] w-[174px] h-[51px] bg-[#ff8181]" />

      <div className="absolute top-[639px] left-[100px] w-[11px] h-3 bg-[#44fcfc]" />

      <button
        className="absolute top-[625px] left-[106px] w-[174px] h-[51px] bg-[#ff8181] cursor-pointer"
        aria-label="Login"
      >
        <span className="absolute top-[15px] left-[46px] w-[88px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
          LOGIN
        </span>
      </button>

      <div className="absolute top-[669px] left-24 w-[7px] h-0.5 bg-[#d9d9d9]" />

      <div className="absolute top-[717px] left-[87px] w-[216px] h-[55px] bg-[#ff7979]" />

      <button
        className="absolute top-[717px] left-[87px] w-[216px] h-[55px] bg-[#ff7979] cursor-pointer"
        aria-label="Register"
      >
        <span className="absolute top-[21px] left-[42px] w-[131px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
          REGISTER
        </span>
      </button>

      <div className="absolute top-[582px] left-[766px] w-[336px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-2xl tracking-[0] leading-[normal]">
        LOGIN
      </div>
    </div>
  );
};

```




# OUTPUT:
![alt text](<Screenshot 2025-10-08 131854.png>)


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
