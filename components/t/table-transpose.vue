<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qa7jj2b-r"/><path class="mqiid19cs"/><path class="cjif5bwva"/><path class="zllb3kbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:table-transpose" /></template>
<style>
.cjif5bwva {
  d: path("M6.75 6.5V15m4-8.5V15M2.5 10.75H15m2.5-7.25c3.5 2.5 4 10.5.5 14c-2.5 2.5-7 3.25-11.5 2.75");
}

.mqiid19cs {
  fill: currentColor;
  d: path("M2.5 2.5H15v4H2.5Z");
}

.qa7jj2b-r {
  d: path("M2.5 2.5H15V15H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zllb3kbhq {
  d: path("M8.75 18L6.5 20.25L8.75 22");
}

</style>
