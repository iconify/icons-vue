<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g3ahzbc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:superhexagon" /></template>
<style>
.g3ahzbc9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.22 21l-3.01 11.21L21 35.22L12.79 27l3-11.21l11.21-3l2.49-9.29l-20.5 5.49l-5.49 20.5L18.51 44.5l20.5-5.49l5.49-20.5z");
}

</style>
