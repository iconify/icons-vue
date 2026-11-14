<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="njkvcdh6k"/><path class="o0g6eve4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:negotiator" /></template>
<style>
.njkvcdh6k {
  d: path("m2.5 10.75l4-4H10l5.75 5.75a1.5 1.5 0 0 1-2 2l-2.25-2.25");
}

.o0g6eve4n {
  d: path("m21.5 10.75l-4-4h-5L10 9.25m-5 4.5l3.5 3.5h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
