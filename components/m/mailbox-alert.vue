<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d0izipbnv"/><path class="lnn6w3bfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mailbox-alert" /></template>
<style>
.d0izipbnv {
  d: path("M7 8h10a4.25 4.25 0 0 1 4.25 4.25V19H2.75v-6.75A4.25 4.25 0 0 1 7 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lnn6w3bfq {
  d: path("M11.25 19v-6.5a4 4 0 0 0-1.17-2.83M14.5 19v2.25M17 13V2.75h3.5V5.5H17");
}

</style>
