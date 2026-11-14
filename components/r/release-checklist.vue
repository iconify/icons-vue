<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="slt7yqvnj"/><path class="ok04giybh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:release-checklist" /></template>
<style>
.ok04giybh {
  d: path("M9 2h6v3H9ZM7.5 9l1.25 1.25L11 8m2 1h3.5m-9 4.25l1.25 1.25L11 12.25m2 1h3.5m-9 4.25l1.25 1.25L11 16.5m2 1h3.5");
}

.slt7yqvnj {
  d: path("M4.5 3.5h15V22h-15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
