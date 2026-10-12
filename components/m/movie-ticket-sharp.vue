<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t_oyg8olp"/><path class="hs_-kjb3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:movie-ticket-sharp" /></template>
<style>
.hs_-kjb3p {
  d: path("M10.75 9.58L14 11.67l.5.33l-.5.33l-3.25 2.09l-.5.33v-5.5z");
}

.t_oyg8olp {
  d: path("M2.75 7.75v-2h18.5V9.5a2.5 2.5 0 0 0 0 5v3.75H2.75V14.5a2.5 2.5 0 0 0 0-5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
