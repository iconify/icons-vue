<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w4hg72bzc"/><path class="wws34lbrr"/><path class="tloly4b5q"/><path class="p8dszccnh"/><path class="qrtoedc3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:money-roll-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8dszccnh {
  d: path("M9 5V19");
}

.qrtoedc3h {
  d: path("M15 5V19");
}

.tloly4b5q {
  d: path("M15 9C16.6569 9 18 10.3431 18 12C18 13.6569 16.6569 15 15 15");
}

.w4hg72bzc {
  d: path("M15 5H9C6.19108 5 4.78661 5 3.77772 5.67412C3.34096 5.96596 2.96596 6.34096 2.67412 6.77772C2 7.78661 2 9.19108 2 12C2 14.8089 2 16.2134 2.67412 17.2223C2.96596 17.659 3.34096 18.034 3.77772 18.3259C4.12468 18.5577 4.51843 18.7098 5 18.8096M9 19H15C17.8089 19 19.2134 19 20.2223 18.3259C20.659 18.034 21.034 17.659 21.3259 17.2223C22 16.2134 22 14.8089 22 12C22 9.19108 22 7.78661 21.3259 6.77772C21.034 6.34096 20.659 5.96596 20.2223 5.67412C19.8753 5.44229 19.4816 5.29018 19 5.19039");
}

.wws34lbrr {
  d: path("M9 15C7.34315 15 6 13.6569 6 12C6 10.3431 7.34315 9 9 9");
}

</style>
