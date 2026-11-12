<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vk6q_hbyk"/><path class="nwzl3abzk"/><path class="drurmkqhp"/><path class="y-na78bap"/><path class="nk7xm8bgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-2-broken" /></template>
<style>
.drurmkqhp {
  stroke-linejoin: round;
  d: path("M16.5121 11.0061H16.5122");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk7xm8bgk {
  stroke-linejoin: round;
  d: path("M6.50061 11.0012H6.50071");
}

.nwzl3abzk {
  d: path("M11.7286 21V18M17.7303 20V17M5.72681 20V17");
}

.vk6q_hbyk {
  d: path("M2.73132 9C3.60686 8.25047 5.00457 7.62664 6.72691 7.21094L6.75528 7.20982M2.73132 12.6524C4.35479 14.0422 7.77356 14.9999 11.7284 14.9999C17.2529 14.9999 21.7313 13.1313 21.7313 10.8262C21.7313 9.65873 20.5824 8.60321 18.7307 7.84573C18.1321 7.6009 17.4602 7.38721 16.7299 7.21094L16.7017 7.20761M11.7286 9C8.53782 9 7.34111 8.4684 6.9269 8.18039C6.78134 8.07918 6.72713 7.90601 6.72713 7.72876C6.72713 7.55339 6.73668 7.38024 6.75528 7.20982M6.75528 7.20982C7.01378 4.84235 9.02031 3 11.4573 3H11.9999C14.4361 3 16.4422 4.8412 16.7017 7.20761C16.7204 7.37874 16.7301 7.55263 16.7301 7.72876C16.7301 7.90601 16.6756 8.07943 16.53 8.18061C16.2489 8.37597 15.6079 8.68323 14.2293 8.86075");
}

.y-na78bap {
  stroke-linejoin: round;
  d: path("M11.5 12H11.5001");
}

</style>
