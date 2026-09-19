<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l97cuw-4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trustdock" /></template>
<style>
.l97cuw-4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.25 26.53V7.47L24 4.53L8.75 7.47v19.06c0 3.17 1.621 6.174 3.813 8.747V10.426L24 8.22l11.438 2.205v24.85c-1.163 1.366-2.486 2.61-3.812 3.693V13.38L24 11.91l-7.625 1.47v25.588a36 36 0 0 0 3.816 2.718l-.003-25.35L24 15.602l3.813.735l-.003 25.35c-1.85 1.138-3.323 1.783-3.81 1.783V19.292");
}

</style>
