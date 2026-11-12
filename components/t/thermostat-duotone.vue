<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w0lv7f-we"/><path class="hzl0s5-6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thermostat-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hzl0s5-6m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m7-5v6m-2 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6-7h2m-2 3h1");
}

.w0lv7f-we {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107");
}

</style>
