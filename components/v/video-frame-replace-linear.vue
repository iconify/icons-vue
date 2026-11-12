<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="plbs7_b_u"/><path class="fyp478bsy"/><path class="w357jhe3h"/><path class="z9zrhebnw"/><path class="e3zt21b_v"/><path class="rkninmigh"/><path class="cgwp-jise"/><path class="uv3603bjt"/><path class="mxjwe0bkt"/><path class="rrznc8wdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-replace-linear" /></template>
<style>
.cgwp-jise {
  d: path("M2.5 6L6 6M11 6L15 6");
}

.e3zt21b_v {
  d: path("M11 2.5V10");
}

.fyp478bsy {
  d: path("M14 22H17C18.8856 22 19.8284 22 20.4142 21.4142C21 20.8284 21 19.8856 21 18C21 16.1144 21 15.1716 20.4142 14.5858C19.8284 14 18.8856 14 17 14H14C12.1144 14 11.1716 14 10.5858 14.5858C10 15.1716 10 16.1144 10 18C10 19.8856 10 20.8284 10.5858 21.4142C11.1716 22 12.1144 22 14 22Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mxjwe0bkt {
  stroke-linejoin: round;
  d: path("M21 11V10C21 9.06812 21 7.60218 20.8478 7.23463C20.6448 6.74458 20.2554 6.35523 19.7654 6.15224C19.3978 6 18.9319 6 18 6M20 10L21 11L22 10");
}

.plbs7_b_u {
  d: path("M6 10H11C12.8856 10 13.8284 10 14.4142 9.41421C15 8.82843 15 7.88562 15 6C15 4.11438 15 3.17157 14.4142 2.58579C13.8284 2 12.8856 2 11 2H6C4.11438 2 3.17157 2 2.58579 2.58579C2 3.17157 2 4.11438 2 6C2 7.88562 2 8.82843 2.58579 9.41421C3.17157 10 4.11438 10 6 10Z");
}

.rkninmigh {
  d: path("M17.5 14.5V22");
}

.rrznc8wdy {
  stroke-linejoin: round;
  d: path("M3 13V14C3 14.9319 3 16.3978 3.15224 16.7654C3.35523 17.2554 3.74458 17.6448 4.23463 17.8478C4.60218 18 5.06812 18 6 18M4 14L3 13L2 14");
}

.uv3603bjt {
  d: path("M11 18H13.5M17.5 18H21");
}

.w357jhe3h {
  d: path("M6 2.5V10");
}

.z9zrhebnw {
  d: path("M13.5 14.5V22");
}

</style>
