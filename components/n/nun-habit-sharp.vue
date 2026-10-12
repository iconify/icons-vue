<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ukawisspm"/><path class="zmn27sbrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nun-habit-sharp" /></template>
<style>
.ukawisspm {
  d: path("M12 2.75c4.5 0 7.25 3.5 7.25 8v10.5H4.75v-10.5c0-4.5 2.75-8 7.25-8Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zmn27sbrf {
  d: path("M12 7c2 0 3.5 1.75 3.5 4S14 15.25 12 15.25s-3.5-2-3.5-4.25S10 7 12 7ZM8.25 18.5L12 17l3.75 1.5");
}

</style>
