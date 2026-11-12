<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fqqct-b5x"/><path class="rvg5dwd0q"/><path class="k4bytsftl"/><path class="hn0mec2mq"/><path class="v31cxj-zs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-smartphone-broken" /></template>
<style>
.fqqct-b5x {
  d: path("M11 17H8C5.17157 17 3.75736 17 2.87868 16.1213C2 15.2426 2 13.8284 2 11V10C2 6.22876 2 4.34315 3.17157 3.17157C3.64118 2.70197 4.2255 2.4206 5 2.25201M22 8.5C22 6.16537 22 4.99805 21.5277 4.11441C21.1548 3.4167 20.5833 2.84525 19.8856 2.47231C19.0019 2 17.8346 2 15.5 2H10C9.65081 2 9.31779 2 9 2.00093");
}

.hn0mec2mq {
  stroke-linejoin: round;
  d: path("M8 22H11V17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4bytsftl {
  d: path("M19 20H17");
}

.rvg5dwd0q {
  d: path("M14 15C14 13.1144 14 12.1716 14.5858 11.5858C15.1716 11 16.1144 11 18 11C19.8856 11 20.8284 11 21.4142 11.5858C22 12.1716 22 13.1144 22 15V18C22 19.8856 22 20.8284 21.4142 21.4142C20.8284 22 19.8856 22 18 22C16.1144 22 15.1716 22 14.5858 21.4142C14 20.8284 14 19.8856 14 18V15Z");
}

.v31cxj-zs {
  d: path("M11 13H2");
}

</style>
