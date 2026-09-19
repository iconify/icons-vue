<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mj3a_md1p"/><path class="vjuszsbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:refra" /></template>
<style>
.mj3a_md1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.532 25.705L5.793 38.95L17.19 5z");
}

.vjuszsbch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.946 22.221l28.26-13.693L30.514 43zm12.25-6.037l-4.765 15.224");
}

</style>
