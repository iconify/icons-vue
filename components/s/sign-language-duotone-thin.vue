<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6kdjab3n"/><path class="avf-3ybgy"/><path class="yhc-cm80y"/><path class="qnm4x6bjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sign-language-duotone-thin" /></template>
<style>
.avf-3ybgy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 21v-8a2 2 0 0 0 -4 0V9a2 2 0 0 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnm4x6bjh {
  d: path("M20 21v-8a2 2 0 0 0 -4 0V9a2 2 0 0 0 -4 0");
}

.w6kdjab3n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yhc-cm80y {
  d: path("M4 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v6");
}

</style>
