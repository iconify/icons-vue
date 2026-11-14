<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oq4ltzbkk"/><path class="kqfziyxex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rfid-tag-clothing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqfziyxex {
  d: path("M9.702 15.702a3.25 3.25 0 0 1 4.596 0m-6.48-2.347a6.25 6.25 0 0 1 8.364 0");
}

.oq4ltzbkk {
  d: path("m7.05 6.213l3.375-2.532a2.625 2.625 0 0 1 3.15 0l3.375 2.532a2.63 2.63 0 0 1 1.05 2.1v10.562a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 6 18.875V8.313a2.63 2.63 0 0 1 1.05-2.1M12 7h.01M12 18h.01");
}

</style>
