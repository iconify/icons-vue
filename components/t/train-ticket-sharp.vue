<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t_oyg8olp"/><path class="sko2mccpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:train-ticket-sharp" /></template>
<style>
.sko2mccpi {
  d: path("M9.25 8.75h3.25v4.75H7.75V8.75zm6.25-1v.75m0 3v1m0 3v.75");
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
