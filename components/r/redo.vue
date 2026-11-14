<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j2lx7tb_b"/><path class="dbt793l7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:redo" /></template>
<style>
.dbt793l7s {
  d: path("m15.5 5.5l4 4l-4 4");
}

.j2lx7tb_b {
  d: path("M19.5 9.5h-10a5 5 0 0 0 0 10H15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
