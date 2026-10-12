<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ofidmqbqd"/><path class="lkdkpirkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-ringing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkdkpirkg {
  d: path("M17.5 2.75a2.9 2.9 0 0 1 2.9 2.9V8l.85 1.5h-7.5L14.6 8V5.65a2.9 2.9 0 0 1 2.9-2.9m-1 9h2");
}

.ofidmqbqd {
  d: path("M5.6 3.25h2.6a1 1 0 0 1 .95.68l1.1 3.3A1 1 0 0 1 10 8.25l-1.6 1.6a12.5 12.5 0 0 0 5.75 5.75l1.6-1.6a1 1 0 0 1 1.02-.25l3.3 1.1a1 1 0 0 1 .68.95v2.6a2.35 2.35 0 0 1-2.35 2.35c-8.3 0-15.15-6.85-15.15-15.15A2.35 2.35 0 0 1 5.6 3.25");
}

</style>
