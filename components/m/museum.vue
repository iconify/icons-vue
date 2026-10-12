<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au1en0b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:museum" /></template>
<style>
.au1en0b7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.1 7.97l7.05-4.44q.85-.53 1.7 0l7.05 4.44q.85.53-.15.53H4.25q-1 0-.15-.53m2.4 3.53V18m3.75-6.5V18m3.5-6.5V18m3.75-6.5V18M3.25 20.75h17.5");
}

</style>
