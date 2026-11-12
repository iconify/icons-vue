<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t-d1zfbuf"/><path class="wa25nab9h"/><path class="cj64798lz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-2-line-duotone" /></template>
<style>
.cj64798lz {
  d: path("M13.8884 3.66309C13.8884 3.66309 13.9811 5.23878 15.3714 6.6291C16.7617 8.01942 18.3374 8.11211 18.3374 8.11211M5.7587 17.7427L4.25781 16.2418");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t-d1zfbuf {
  d: path("M4 22H20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wa25nab9h {
  d: path("M13.8881 3.66293L14.6296 2.92142C15.8581 1.69286 17.85 1.69286 19.0786 2.92142C20.3071 4.14999 20.3071 6.14188 19.0786 7.37044L18.3371 8.11195L11.5201 14.9289L11.5201 14.929C11.0583 15.3907 10.8275 15.6215 10.5729 15.8201C10.2727 16.0543 9.94775 16.2551 9.60398 16.4189C9.31256 16.5578 9.00284 16.6611 8.3834 16.8675L8.38334 16.8675L5.75834 17.7426L5.11667 17.9564C4.81182 18.0581 4.47573 17.9787 4.2485 17.7515C4.02128 17.5243 3.94194 17.1882 4.04356 16.8833L4.25745 16.2417L5.13245 13.6167C5.33894 12.9972 5.44219 12.6874 5.58107 12.396C5.74491 12.0522 5.94571 11.7273 6.17992 11.4271C6.37846 11.1725 6.60933 10.9416 7.07106 10.4799L13.8881 3.66293Z");
}

</style>
