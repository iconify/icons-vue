<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bcnjt0r8l"/><path class="ge6cvbb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:query-run" /></template>
<style>
.bcnjt0r8l {
  d: path("M12.2 20.5H2.5v-17h19v11.3m-19-7.05h19");
}

.ge6cvbb7b {
  d: path("M7 10.5L4.5 13L7 15.5m3.5-5.5l-1.75 6M15 14.5l6.5 3.5l-6.5 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
