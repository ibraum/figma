<script setup lang="ts"></script>

<template>
  <section class="w-full h-screen relative bg-[url(/grid.png)]">
    <header class="w-full absolute mt-6 px-4">
      <div class="max-w-[1080px] w-full h-10 mx-auto flex items-center justify-between">
        <div class="flex items-center justify-start gap-2.5">
          <div
            class="h-10 w-10 rounded-full flex items-center justify-center bg-[#282828]"
          >
            <img src="/logo.png" alt="Figma logo" />
          </div>
          <div class="text-[20px] font-semibold">Figma</div>
        </div>
        <div class="flex items-center justify-center gap-5 text-[14px] max-md:hidden">
          <div class="">Features</div>
          <div class="">Figma Plugin</div>
          <div class="">Value</div>
          <div class="">Pricing</div>
          <div class="">Reviews</div>
        </div>
        <div class="flex items-center justify-end gap-2.5">
          <button
            class="text-[14px] px-5 py-2.5 border border-[#282828] rounded-full cursor-pointer bg-white"
          >
            Login
          </button>
          <button
            class="text-[14px] px-5 py-2.5 text-white bg-[#282828] rounded-full cursor-pointer flex items-center justify-center gap-1"
          >
            <div class="">Sign up</div>
            <img src="/arrow.png" alt="Arrow" />
          </button>
        </div>
      </div>
    </header>
    <main class="w-full h-full flex flex-col items-center justify-center gap-[35px]">
    
      <div class="flex items-center justify-center gap-[55px] relative max-md:flex-wrap max-md:gap-5">
      <img src="/user_chilling.png" class="absolute -bottom-30 -left-24 max-xl:left-0 max-xl:bottom-2"  alt="User chilling">
      <img src="/user_ibraum.png" class="absolute -top-12 -right-24 max-xl:right-2"  alt="User chilling">
        <img src="/Design_f.png" class="duration-300 hover:mb-4" alt="f">
        <img src="/Design_f-1.png" class="duration-300 hover:mb-2" alt="f1">
        <img src="/Design_f-2.png" class="duration-300 hover:mb-2" alt="f2">
        <img src="/Design_f-3.png" class="duration-300 hover:mb-2" alt="f3">
        <img src="/Design_f-4.png" class="duration-300 hover:mb-2" alt="f4">
      </div>
      <div class="max-w-[600px] max-md:px-4 w-full text-[14px] text-center font-normal leading-6">
      Designed in Figma, this project focuses on clean, modern UI and seamless user experience. Built with scalable components and auto layout for consistency and flexibility. Interactive prototypes showcase smooth flows and responsive design across devices.
      </div>
              <div class="flex items-center justify-start gap-2.5">
          <div
            class="h-10 w-10 rounded-full flex items-center justify-center bg-[#282828]"
          >
            <img src="/logo.png" alt="Figma logo" />
          </div>
                    <button
            class="text-[14px] px-5 py-2.5 border border-[#282828] rounded-full cursor-pointer bg-white"
          >
            Join us to get all gift in time
          </button>
        </div>
    </main>
    <div class="w-full absolute max-md:bottom-4 bottom-11 px-4">
      <div
        class="relative max-w-[1080px] w-full px-[30px] py-[15px] mx-auto flex max-md:flex-col  items-center justify-between max-md:items-start gap-6 bg-[#FAC51F] border-3 rounded-[20px] flex items-center justify-between">
          <img src="/close_buttons.png" alt="Close button" class="absolute transform -translate-1/2 top-0 -right-[30px] cursor-pointer">
          <div class="flex flex-col itemls-start justify-center gap-2.5">
            <div class="text-[15px] leading-[15px] font-black">50% OFF | ONLINE EXCLUSIVE</div>
            <div class="text-[14px] leading-[20px] font-normal">Book on line and get 50% off your general Admission ticket available this week-ends</div>
          </div>    
                    <button
            class="text-[14px] px-5 py-2.5 text-white bg-[#282828] rounded-full cursor-pointer flex items-center justify-center gap-1"
          >
            <div class="font-semibold">Claim 50% OFF</div>
          </button>    
        </div>
    </div>
  </section>
</template>
