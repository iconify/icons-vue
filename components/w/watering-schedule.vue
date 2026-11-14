<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ymvqec_al"/><path class="phxe8d87v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:watering-schedule" /></template>
<style>
.phxe8d87v {
  d: path("M12 18.5v-4c0-2 1.5-2.75 3.5-2.75c0 2-1.5 2.75-3.5 2.75m0 1.5c-2 0-3.5-1-3.5-3c2 0 3.5 1 3.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymvqec_al {
  d: path("M3 4.5h18v17H3ZM3 9h18M8 2.5v4m8-4v4");
}

</style>
