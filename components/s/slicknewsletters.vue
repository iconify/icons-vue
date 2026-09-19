<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f9_mikb3k"/><path class="ckm2ambrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:slicknewsletters" /></template>
<style>
.ckm2ambrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.87 8.465l1.351 13.428L43.5 23.755");
}

.f9_mikb3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.755 39.536L6.31 26.306c-2.236-1.702-2.498-6.702-.239-8.914L19.87 8.465l23.63 15.29l-12.067 7.807a4.78 4.78 0 0 0-2.41 4.207c-.008 1.467.848 3.439 2.41 3.038L43.5 30.999l-5.325-3.445");
}

</style>
