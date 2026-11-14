<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_5smibgm"/><path class="gkrxfmbzu"/><path class="d7f-kccvt"/><path class="p3j4k2tpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sick-leave" /></template>
<style>
.c_5smibgm {
  d: path("M12.7 20.5H3.5V5h17v6.4M8 3v4m8-4v4M3.5 10h17");
}

.d7f-kccvt {
  d: path("M16.75 18v-2.75c0-.85.65-1.5 1.5-1.5s1.5.65 1.5 1.5V18c.75.5 1.25 1.25 1.25 2c0 1.1-1.25 2-2.75 2s-2.75-.9-2.75-2c0-.75.5-1.5 1.25-2Z");
}

.gkrxfmbzu {
  fill: currentColor;
  d: path("M6.25 12.25h4.5v4h-4.5Z");
}

.p3j4k2tpi {
  fill: currentColor;
  d: path("M17.25 20a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
