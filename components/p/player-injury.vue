<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eo0w5-bij"/><path class="lp35ljv5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:player-injury" /></template>
<style>
.eo0w5-bij {
  d: path("M4.5 7.75a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM3.25 21.5c0-4.5 3-6 6.25-6c2.442 0 4.742.847 5.736 3.176");
}

.lp35ljv5v {
  d: path("M4.5 6.75h10l3-2.25m-3 2.25l3 2.25m.5 5.75v3.5M18 21h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
