<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            name: "Smoljames Store",
            icon: "fa-solid fa-cart-shopping",
            description:
                "Smoljames Store is a a merchanising store created with Next.js, Commerce.js & Stripe! Commerce.js is a CMS for managing project and Stripe is used for all transaction handling.",
        },
        {
            name: "Utlimate Todos",
            icon: "fa-solid fa-list-check",
            description:
                "Test for model robustness with customized test profiles and receive exhaustive reporting on the performance and potential vulnerabilities of your model.",
        },
        {
            name: "Pokédex",
            icon: "fa-solid fa-diagram-project",
            description:
                "Augment your datasets with our filters and dataset manipulations to ensure your models are trained on the highest quality datasets (coming soon).",
        },
    ];

    let benefits = [
        {
            metric: "10x",
            name: "a self taught developer",
            description:
                "I taught myself to code using free online resources and absolutely fell in love with the creativity and problem solving that is involved in developing and engineering innovative new online experiences. Starting of with JavaScript, HTML & CSS and evolving my knowledge base to include JavaScript frameworks, backend programming, design, cloud services and much much more.",
        },
        {
            name: "a product design & UX finatic",
            description:
                "Carefully crafting and designing amazing user experiences allows me to express and experiment with every morsel of creativity I have. I love the challenge of learning new design concepts and enabling users with amazing online experiences.",
        },
        {
            name: "an excellent communicator",
            description:
                "Communication is key and it's a paramount value of mine. I believe in transparency and constructive communication above all else. This helps me develop deep relationships and ensures my effectiveness and productivity in any work space with any team.",
        },
    ];
</script>

<main class="flex flex-col flex-1 p-4">
    <section
        id="introPage"
        class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
    >
   
        <div
            class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
        >
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Email for <span class="poppins text-white-400">
                    <br>Developers</span> 
                <br />
                <span class="poppins text-violet-100"></span>
            </h2>
            <p class="text-base sm:text-lg md:text-xl">
                The <span class="text-white-400">best way to reach </span> human instead of spam folders.
                Deliver transactional and marketing emails at scale.
            </p>
            
       
            <button
                class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
            >
                <div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                />
                <h4 class="relative z-9">Get started &rarr;</h4>
            </button>
            <button>
                <div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                />
                <h4 class="relative z-9">Documentation &rarr;</h4>
            </button>
            </div>
            <div class="relative shadow-2x1 grid place-items-center">
                <img
                    src={"images/cube.png"}
                    alt="Cube"
                    class="object-cover z-[2] max-h-[70vh] max-w-[80vh]"
                />
            </div>
        <br>
        <div class="flex flex-col gap-2 text-centre"></div>
        <h6 class="text-large sm:text-xl md:text-2xl">
           Backed by Y Combinator
        </h6>
       
        <!-- <div  class="flex p-0.5 relative max-w-[700px] w-full mx-auto">
            <div
                class="absolute inset-0 overflow-hidden rounded-md flex items-center justify-center"
            >
                <div
                    class="bg-gradient-to-r absolute inset-[-20px]  from-violet-800 to-indigo-800 specialSpin"
                />
            </div>

            <img
                src={"images/zetane-engine.jpeg"}
                alt="Zetane Engine"
                class="w-full h-full object-cover z-[2]"
            />
        </div> -->
    </section>
    <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
        <div class="flex flex-col gap-2 text-center">
            <h6 class="text-large sm:text-xl md:text-2xl">
                Companies of all sizes trust Resend <br>to deliver their most important emails.
            </h6>
           
        </div>
      
        <div class="relative shadow-2xl grid place-items-centre">
            <img src ={"images/comp.png"} alt="Company Logo" class="object-cover z-[2] max-h-[70vh]"/>
        </div>
        
         
        
    </section>
    <section
        id="about"
        class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
    >
        <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
        <div>
            <div class="relative shadow-2x1 grid place-items-center">
            <img src ={"images/inbox.png"} alt="Inbox Logo" class="object-cover z-[2] max-h-[30vh]"/></div><br>
            <h1 class={" text-3xl sm:text-3xl font-semibold text-center poppins "}>
                Integrate <span class="text-yellow-400">this morning</span>
            </h1>
            
                <h6 class="text-large sm:text-xl md:text-2xl text-center">
                <br> A simple, elegant interface so you can start sending emails in minutes. It fits
                 <br>right into your code with SDKs for your favorite programming languages.
             </h6>
            
        </div>
       
        <div>

          
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                First-class 
                <br>developer experience 
            </h3>
            <h6 class="text-large sm:text-xl md:text-2xl">
               <br> We are a team of engineers who love building tools for other engineers.
                <br>Our goal is to create the email platform we've always wished we had — one that just works.
            </h6>

            
        </div>
        <h3 class={" text-2xl sm:text-3xl font-semibold text-left poppins "}>
            Test Mode 
        </h3>
        <h8 class="text-large sm:text-2xl md:text-2xl">
             Simulate events and experiment with our API
             <br>
             without the risk of accidentally sending real 
             <br>emails to real people.
<br>
<br>
            Learn more
         </h8>

         <h3 class={" text-2xl sm:text-3xl font-semibold text-right poppins "}>
            Modular Webhooks
        </h3>
        <h8 class="text-large sm:text-2xl text-right">
            Receive real-time notifications directly to your
             <br>
             server. Every time an email is delivered, opened,
             <br>bounces, or a link is clicked.
         <br>
         <br>
            Learn more
         </h8>

        
    </section>
      <section>
        <div class="relative shadow-2x1 grid place-items-center">
            <img src ={"images/react.png"} alt="Inbox Logo" class="object-cover z-[2] max-h-[30vh]"/></div><br>
            <div>
            <h1 class="font-semibold text-3xl sm:text-4xl text-center">
                Develop emails using React
            </h1>
           
        </div>
        <div>
            <h6 class="text-small sm:text-xl md:text-2xl text-center">
                <br> Create beautiful templates without having to deal with table  layouts and HTML.
                 <br>Powered by react-email, our open source component library.
             </h6>
            
                
        </div><br>
        <div>
            <button
            class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full bg-white text-slate-950  text-center"
        >
        <p class="px-4 py-2 bg-white text-slate-950 font-medium">
            Get started 
        </p>
     </button>
     </div>
     <br>

        <button
        class="blueShadow relative overflow-hidden px-1 py-77 group rounded-full bg-grey text-white-950"
        >
            <div
                class="absolute top-2 left-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-10 z-0 duration-200"
            />
            <h4 class="relative z-9">Check The Docs ></h4>
         </button>  
         
       
            <div>
                <h6 class="text-small sm:text-xl md:text-2xl text-center">
                    <br>Resend is transforming email for developers.
                     <br>Simple interface, easy integrations, handy
                     <br>templates. What else could we ask for.<br><br><br><br><br><br>
                 </h6>
          
        </div>
         <div class="relative shadow-2x1 grid place-items-center">
            <img src ={"images/globe.png"} alt="Inbox Logo" class="object-cover z-[2] max-h-[30vh]"/></div>
            <div>
            <h1 class="font-semibold text-3xl sm:text-4xl text-center">
                Everything in your control
            </h1>
            <h6 class="text-small sm:text-xl md:text-2xl text-center">
                <br>All the features you need to manage your email sending, troubleshoot with
                 <br>detailed logs, and protect your domain reputation – without the friction.
                 
             </h6>

            </div>
            <div class="relative shadow-2x1 grid place-items-center">
                <img src ={"images/graph.png"} alt="Inbox Logo" class="object-cover z-[2] max-h-[150vh]"/></div>
                <div>
                    
                    <h1 class="font-semibold text-3xl sm:text-4xl text-center">
                        <br><br><br><br><br>  Beyond expectations.<br>
                      </h1>
                      <h6 class="text-small sm:text-xl md:text-2xl text-center">
                        Resend is driving remarkable developer experiences that enable success<br>
                        stories, empower businesses, and fuel growth across industries and individuals.<br>
                     </h6>
                </div>
                <div>
                    
                    <h1 class="font-semibold text-3xl sm:text-4xl text-center">
                      <br> <br><br><br><br> Email reimagined.<br>Available today.<br>
                    </h1>
                    </div>
                    <div>
                        <button
                        class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full bg-white text-slate-950  text-center"
                    >
                    <p class="px-4 py-2 bg-white text-slate-950 font-medium">
                        Get started &darr;
                    </p>
                    </div>
                    <div><br>
                        <button
        class="blueShadow relative overflow-hidden px-1 py-77 group rounded-full bg-grey text-white-950"
        >
            <div
                class="absolute top-2 left-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-10 z-0 duration-200"
            />
            <h4 class="relative z-9">Contact Us ></h4>
         </button>  
                    </div>
                    <div class="relative shadow-2x1 grid place-items-center">
                        <br><br><br><br>
                        <img src ={"images/resend.png"} alt="Inbox Logo" class="object-cover z-[2] max-h-[150vh]"/></div>
            



                        

      </section>
</main>
