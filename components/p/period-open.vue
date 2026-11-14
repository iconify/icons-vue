<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pe17-8b7q"/><path class="g4q0dt5qu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:period-open" /></template>
<style>
.g4q0dt5qu {
  d: path("M16.75 17.5v-2.75a2 2 0 0 1 4 0v.5");
}

.pe17-8b7q {
  d: path("M12.2 21H2.5V4.5H19V10M7 2.5v4m7.5-4v4m-12 3H19m-4 8h6.5V22H15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
