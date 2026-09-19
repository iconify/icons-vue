<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qpgc8sblw"/><circle class="chdt74bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-spectrum" /></template>
<style>
.chdt74bhh {
  cx: 24.412px;
  cy: 15.074px;
  r: 9.574px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qpgc8sblw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.865 42.5c0-9.867-7.998-17.865-17.865-17.865S6.135 32.633 6.135 42.5z");
}

</style>
