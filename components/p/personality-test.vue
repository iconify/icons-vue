<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oda4a2bll"/><path class="v_zihhbcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:personality-test" /></template>
<style>
.oda4a2bll {
  d: path("M3 3.5h18v17H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_zihhbcu {
  d: path("M12 8c-2-2-5.5-1.5-5.5 1.75c0 2 2 2.75 3.5 2.75c-1.5 1-1.75 3.75.25 4c1 .25 1.5-1 1.75-2c.25 1 .75 2.25 1.75 2c2-.25 1.75-3 .25-4c1.5 0 3.5-.75 3.5-2.75C17.5 6.5 14 6 12 8Z");
}

</style>
