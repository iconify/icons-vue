<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwkstmbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rain-boots-kids" /></template>
<style>
.zwkstmbtz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h5v7c2 0 3 1.25 3 3.5v3h-8Zm11 0h5v7c2 0 3 1.25 3 3.5v3h-8Zm-11 3h5m6 0h5");
}

</style>
