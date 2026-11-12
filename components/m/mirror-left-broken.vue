<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dufqe1b5r"/><path class="rss4ctb5l"/><path class="cipdabcte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-left-broken" /></template>
<style>
.cipdabcte {
  d: path("M12 22L12 2");
}

.dufqe1b5r {
  d: path("M3 12C3 16.2426 3 18.364 4.31802 19.682C5.63604 21 7.75736 21 12 21M12 3C7.75736 3 5.63604 3 4.31802 4.31802C3.50241 5.13363 3.19151 6.25685 3.073 8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rss4ctb5l {
  d: path("M11 21H11.9091M11 3H11.9091M14.0909 3H15C15.4354 3 15.8373 3 16.2089 3.00321M19.0874 3.27719C19.5057 3.40719 19.8408 3.59815 20.1213 3.87868C20.4018 4.15921 20.5928 4.49432 20.7228 4.91261M20.9968 7.79109C21 8.16269 21 8.56459 21 9V10.3636M21 13.6364V15C21 15.4354 21 15.8373 20.9968 16.2089M20.7228 19.0874C20.5928 19.5057 20.4018 19.8408 20.1213 20.1213C19.8408 20.4018 19.5057 20.5928 19.0874 20.7228M16.2089 20.9968C15.8373 21 15.4354 21 15 21H14.0909");
}

</style>
