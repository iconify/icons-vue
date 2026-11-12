<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jvzm0ac7t"/><path class="jfoq-1h6n"/><path class="u3tqh8b-y"/><path class="z3ylw7bis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfoq-1h6n {
  d: path("M2 14C5.77124 14 7.65685 14 8.82843 15.1716C10 16.3431 10 18.2288 10 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.jvzm0ac7t {
  d: path("M14 22C14 18.2288 14 16.3431 15.1716 15.1716C16.3431 14 18.2288 14 22 14");
}

.u3tqh8b-y {
  d: path("M2 10C5.77124 10 7.65685 10 8.82843 8.82843C10 7.65685 10 5.77124 10 2");
}

.z3ylw7bis {
  d: path("M22 10C18.2288 10 16.3431 10 15.1716 8.82843C14 7.65685 14 5.77124 14 2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
