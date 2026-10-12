<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="su4rm4ssb"/><path class="zzd3robdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spaghetti" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.su4rm4ssb {
  d: path("M2.75 17h18.5c-.5 2.5-3 4.25-6 4.25h-6.5c-3 0-5.5-1.75-6-4.25M11 6.5a4.75 3.5 0 1 1 0 7a4.75 3.5 0 1 1 0-7");
}

.zzd3robdi {
  d: path("M6.25 9.75c3 1 6.5 1 9.5 0m-6.5 3.65c-.75 1.25.75 2.35 0 3.6m4.8-9.68l4.57-4.57");
}

</style>
