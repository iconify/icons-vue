<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ifob98x5h"/><path class="wsz-fhheg"/><path class="st5qv8h2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:message-quote-sharp" /></template>
<style>
.ifob98x5h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

.st5qv8h2h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9.5v2.474l-2.25.776M15.5 9.5v2.474l-2.25.776");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wsz-fhheg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9.5h.01m5.49 0h.01");
}

</style>
