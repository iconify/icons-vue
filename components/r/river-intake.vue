<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uzlyx6bdw"/><path class="j_fogebxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:river-intake" /></template>
<style>
.j_fogebxy {
  d: path("M6.5 3L4 5.5L6.5 8M2 16q2.5-2 5 0t5 0t5 0t5 0M2 20q2.5-2 5 0t5 0t5 0t5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzlyx6bdw {
  d: path("M2.5 5.5H13A2.5 2.5 0 0 1 15.5 8v4M13 12h5");
}

</style>
