<script setup>
import HomeIcon from "../icons/HomeIcon.vue";
import SettingsIcon from "../icons/SettingsIcon.vue";
import AboutIcon from "../icons/AboutIcon.vue";
import DashboardIcon from "../icons/DashboardIcon.vue";
import TeamIcon from "../icons/TeamIcon.vue";
</script>

<template>
  <nav
    class="sticky left-0 flex h-screen bg-slate-50 border-r border-green-100"
  >
    <ul>
      <li class="p-[2rem] font-bold text-3xl mb-[2rem]">deskbink \\\</li>
      <div>
        <li
          @click="$router.push('/')"
          class="mb-2 focus:bg-green-300 hover:bg-green-300 hover:ease-in-out duration-200 cursor-pointer font-semibold px-6 py-[1rem] w-[13rem] py-[1rem] bg-green-200 rounded-r-3xl hover:w-[15rem]"
        >
          <div class="flex gap-2">
            <HomeIcon />
            Home
          </div>
        </li>
        <li
          @click="$router.push('/dashboard')"
          class="mb-2 focus:bg-green-300 hover:bg-green-300 hover:ease-in-out duration-200 cursor-pointer font-semibold px-6 py-[1rem] w-[13rem] py-[1rem] bg-green-200 rounded-r-3xl hover:w-[15rem]"
        >
          <div class="flex gap-2">
            <DashboardIcon />
            Dashboard
          </div>
        </li>
        <li
          @click="$router.push('/about')"
          class="mb-2 focus:bg-green-300 hover:bg-green-300 hover:ease-in-out duration-200 cursor-pointer font-semibold px-6 py-[1rem] w-[13rem] py-[1rem] bg-green-200 rounded-r-3xl hover:w-[15rem]"
        >
          <div class="flex gap-2">
            <AboutIcon />
            About
          </div>
        </li>
        <li
          class="mb-2 focus:bg-green-300 hover:bg-green-300 hover:ease-in-out duration-200 cursor-pointer font-semibold px-6 py-[1rem] w-[13rem] py-[1rem] bg-green-200 rounded-r-3xl hover:w-[15rem]"
        >
          <div class="flex gap-2">
            <TeamIcon />
            Team
          </div>
        </li>
        <li
          class="mb-2 focus:bg-green-300 hover:bg-green-300 hover:ease-in-out duration-200 cursor-pointer font-semibold px-6 py-[1rem] w-[13rem] py-[1rem] bg-green-200 rounded-r-3xl hover:w-[15rem]"
        >
          <i class="devicon-github-original pr-2"></i>
          <a href="https://github.com/jakeNorman007/deskbink">Github</a>
        </li>
        <li
          class="mb-2 focus:bg-green-300 hover:bg-green-300 hover:ease-in-out duration-200 cursor-pointer font-semibold px-6 py-[1rem] w-[13rem] py-[1rem] bg-green-200 rounded-r-3xl hover:w-[15rem]"
        >
          <div class="flex gap-2">
            <SettingsIcon />
            Settings
          </div>
        </li>
      </div>
    </ul>
  </nav>
</template>
