<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x19_68vnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:press-clipping" /></template>
<style>
.x19_68vnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 3h2.75A2.625 2.625 0 0 1 10.5 5.625v6.75A2.625 2.625 0 0 1 7.875 15h-2.75A2.625 2.625 0 0 1 2.5 12.375v-6.75A2.625 2.625 0 0 1 5.125 3m9.625 14.75L19.5 3m-.25 14.75L14.5 3M12 19.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M5.25 7.5h2.5");
}

</style>
