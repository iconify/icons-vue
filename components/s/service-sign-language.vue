<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yho79rl-l"/><path class="way4twfqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:service-sign-language" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.way4twfqb {
  d: path("M14.5 8V6A1.25 1.25 0 0 1 17 6v8.5c0 4-3 6.5-6 6.5c-2.5 0-4-2-4-4");
}

.yho79rl-l {
  d: path("M7 15V8.5a1.25 1.25 0 0 1 2.5 0V13m0-5V5.5a1.25 1.25 0 0 1 2.5 0V11m0-3V4.5a1.25 1.25 0 0 1 2.5 0V11");
}

</style>
