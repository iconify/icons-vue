<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi23r5bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patient-consent" /></template>
<style>
.oi23r5bie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.875 16l.274-1.097a1.5 1.5 0 0 1 .395-.697l4.395-4.395a1.5 1.5 0 0 1 2.122 0l.128.128a1.5 1.5 0 0 1 0 2.122l-4.395 4.395a1.5 1.5 0 0 1-.697.395L14 17.125A.928.928 0 0 1 12.875 16M2.5 20.5h19m-19-4C4 13 5.5 12.5 6 14s-.5 3.25 1 3.25S9 14 10.25 14.5c.75.25.5 2 1.75 2.25");
}

</style>
