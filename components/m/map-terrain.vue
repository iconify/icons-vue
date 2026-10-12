<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbql_ubow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-terrain" /></template>
<style>
.rbql_ubow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.4 5.75l3.45-1.5q1.15-.5 2.3-.02l3.7 1.54q1.15.48 2.3-.02l3.45-1.5q1.15-.5 1.15.75v11.5q0 1.25-1.15 1.75l-3.45 1.5q-1.15.5-2.3.02l-3.7-1.54q-1.15-.48-2.3.02l-3.45 1.5q-1.15.5-1.15-.75V7.5q0-1.25 1.15-1.75m4.6-2v14m6-11.5v14");
}

</style>
