<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6l0zbi5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oars" /></template>
<style>
.z6l0zbi5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.25L5.5 5.5m1 1l6.75 6.75m1.55.15l4.1 2.25q1.1.6 1.31 1.83l.33 2.04q.21 1.23-1.02 1.02l-2.04-.33q-1.23-.21-1.83-1.31l-2.25-4.1q-.6-1.1-.15-1.55t1.55.15");
}

</style>
