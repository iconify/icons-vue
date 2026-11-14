<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ngkoguy7b"/><path class="mkbj4wpyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ticket-calendar" /></template>
<style>
.mkbj4wpyq {
  d: path("M9 12.5h12.5v2.75a1.75 1.75 0 0 0 0 3.5v2.75H9v-2.75a1.75 1.75 0 0 0 0-3.5Z");
}

.ngkoguy7b {
  d: path("M6.25 17.5H4.5a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v3.25M2.5 8.5h13m-9-6v3.25m5-3.25v3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
