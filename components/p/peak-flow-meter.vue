<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv-ygqbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:peak-flow-meter" /></template>
<style>
.wv-ygqbgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7c-3-.5-7 3.5-7 9c0 2.75 1.5 4.25 3.5 3.75s3.5-1.5 3.5-3.75Zm3 8.012V7c2.538-.423 5.793 2.376 6.734 6.579M12 2.5v5M10.5 9L12 7.5L13.5 9m.75 10.75a3.75 3.75 0 0 1 7.5 0m-7.5 0h7.5m-3.75 0L19.75 17");
}

</style>
