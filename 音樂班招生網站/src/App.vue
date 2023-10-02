<script setup>
import Info from "./components/MusicClass.vue";
</script>

<template>
  <div class="overflow-x-hidden">
    <div class="relative w-screen overflow-x-hidden bg-[#DBCEBB]">
      <div class="min-h-screen flex flex-col items-center">
        <!-- 棋盤格 -->
        <div class="w-full h-[5vw] bg-[#7D5936] flex">
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
        </div>
        <!-- title -->
        <div
          class="w-[56vw] h-[37.8vw] bg-opacity-80 bg-[#FFFFFF] mt-[5vw] text-center rounded-[2vw] flex flex-col items-center justify-center overflow-hidden"
        >
          <div
            class="absolute w-[2vw] h-[2vw] rounded-full bg-[#AC947D] mt-[-30vw] ml-[-48vw]"
          ></div>
          <div
            class="absolute w-[2vw] h-[2vw] rounded-full bg-[#AC947D] mt-[-30vw] ml-[48vw]"
          ></div>
          <div
            class="absolute w-[2vw] h-[2vw] rounded-full bg-[#AC947D] mt-[30vw] ml-[48vw]"
          ></div>
          <div
            class="absolute w-[2vw] h-[2vw] rounded-full bg-[#AC947D] mt-[30vw] ml-[-48vw]"
          ></div>
          <p class="font-bold text-[2.5vw]">臺北市立復興高級中學112學年度</p>
          <p class="font-black text-[3.5vw] my-[2.5vw]">
            音樂班甄選入學 暨術科測驗
          </p>
          <p class="font-bold text-[2.5vw]">招生資訊網</p>
        </div>

        <!-- Information -->
        <p class="text-[6vw] font-bold pt-[8vw] pb-[0.01vw] text-[#AA483B]">
          最新公告
        </p>
        <p class="text-[2.8vw] font-light pb-[3vw] text-[#AA483B]">
          Latest News
        </p>
        <!-- component 1 -->
        <div class="gap-4 grid grid-cols-1 lg:grid-row-2 lg:grid-cols-2">
          <div>
            <Info />
            <div class="p-3"></div>
            <Info />
          </div>
          <div>
            <Info />
            <div class="p-3"></div>
            <Info />
          </div>
        </div>

        <!-- Footer -->
        <div class="p-3 lg:p-6"></div>
        <div
          class="border-2 border-solid border-[#7D5936] rounded-md py-2 px-3 flex flex-col items-center"
        >
          <div class="text-xs text-[#7D5936] font-bold lg:text-xl">
            <p>主辦學校：臺北市立復興高級中學</p>
            <p>主辦單位：藝術組</p>
            <p class="text-[#AA483B]">
              連絡電話：(02)2891-4131分機8101 \ 8102藝術組
            </p>
          </div>
          <!-- web link -->
          <div class="flex justify-center items-center pt-2 gap-10">
            <button
              class="py-1 px-3 border-[#6F5B49] border-solid border rounded-md justify-center text-[#7D5936] font-bold text-sm lg:text-xl"
            >
              音樂班官網
            </button>
            <button
              href=""
              class="py-1 px-3 border-[#6F5B49] border-solid border rounded-md justify-center text-[#7D5936] font-bold text-sm lg:text-xl"
            >
              FB專頁
            </button>
          </div>
          <div class="p-1"></div>
          <div>
            <div class="flex gap-4">
              <p class="text-xs text-[#7D5936] lg:text-xl">
                Designed : 楊沁璇、張語桐
              </p>
              <p class="text-xs text-[#7D5936] lg:text-xl">Mentored : 陳 晉</p>
            </div>
            <div class="flex gap-10">
              <p class="text-xs text-[#7D5936] lg:text-xl">Created : 楊沁璇</p>
              <p class="text-xs text-[#7D5936] lg:text-xl">
                Powered : FHSH IT DEPT
              </p>
            </div>
          </div>
        </div>
        <div class="p-2 lg:p-4"></div>
        <!-- <div class="bg-[#7D5936] w-full h-3 lg:h-7"></div> -->

        <!-- 棋盤格 -->
        <div class="w-full bg-[#7D5936] flex">
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white"></div>
          <div class="w-[2.5vw] h-[2.5vw] bg-white mt-[2.5vw]"></div>
        </div>
      </div>
    </div>
  </div>
</template>
