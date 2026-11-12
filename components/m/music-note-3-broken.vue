<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qpgyrzr1h"/><path class="viuxy1b9m"/><path class="zt3x4widq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-3-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qpgyrzr1h {
  d: path("M12 18C12 20.2091 10.2091 22 8 22C5.79086 22 4 20.2091 4 18C4 15.7909 5.79086 14 8 14C10.2091 14 12 15.7909 12 18Z");
}

.viuxy1b9m {
  d: path("M12 12V6");
}

.zt3x4widq {
  d: path("M13.4833 8.74163L16.1167 10.0583C16.9853 10.4926 17.4196 10.7098 17.7683 10.7504C18.6899 10.858 19.5644 10.3175 19.8804 9.44506C20 9.11498 20 8.62944 20 7.65835C20 7.25036 20 7.04637 19.9643 6.86006C19.872 6.37744 19.6051 5.94571 19.2148 5.64725C19.0641 5.53203 18.8816 5.4408 18.5167 5.25835L15.8833 3.94163C15.0147 3.50734 14.5804 3.2902 14.2317 3.24952C13.3101 3.14202 12.4356 3.68251 12.1196 4.55491C12 4.88499 12 5.37054 12 6.34163C12 6.74962 12 6.95361 12.0357 7.13992C12.128 7.62254 12.3949 8.05426 12.7852 8.35273C12.9359 8.46794 13.1184 8.55917 13.4833 8.74163Z");
}

</style>
