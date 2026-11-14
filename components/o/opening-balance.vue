<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t822f2bsb"/><path class="zb9t40sos"/><path class="y8-m75byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:opening-balance" /></template>
<style>
.t822f2bsb {
  d: path("M4 9.5h3.5l3 3V20A1.5 1.5 0 0 1 9 21.5H4A1.5 1.5 0 0 1 2.5 20v-9A1.5 1.5 0 0 1 4 9.5Zm9.5 0h8v12h-8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y8-m75byh {
  d: path("M14.75 6.5h2.75V3.75");
}

.zb9t40sos {
  d: path("M7.5 9.5v3h3m-4-6q5.5-6 11 0");
}

</style>
