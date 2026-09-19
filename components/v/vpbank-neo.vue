<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kh1-nfb1j"/><path class="lq-m5_wgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vpbank-neo" /></template>
<style>
.kh1-nfb1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.417V40.25m0-23.833l8.667-8.667M24 16.417L15.333 7.75M4.5 19.667h10.833L24 28.333l8.667-8.666H43.5S27.25 40.25 25.083 40.25h-2.166C20.75 40.25 4.5 19.667 4.5 19.667");
}

.lq-m5_wgo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.333 19.667V7.75L24 16.417l8.667-8.667v11.917M24 16.417V40.25");
}

</style>
