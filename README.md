
# what is this 
# get react stepper with horizontal view, include own images and colors for lines etc...


# install module - npm i react-stepper-horizontal-images


# import module on top
# npm install react-stepper-horizontal-images --save


# Then import below lines for stepper design in your code...

<Stepper
            steps={[
              { title: "Register", icon: "../images/step1.png" },
              { title: "Building List", icon: "../images/step2.png" },
              { title: "Choose Schedule", icon: "../images/step3.png" },
              { title: "Payment", icon: "../images/step4.png" },
              { title: "Scheduled", icon: "../images/step5.png" },
            ]}
            activeStep={0}
            completeBarColor={"#248823"}
            defaultBarColor={"#E0E0E0"}
          />


# .....