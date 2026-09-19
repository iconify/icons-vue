<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fm3gxccsh"/><circle class="it5im0gms"/><path class="ja-y9mbes"/><path class="ohhfn9bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pbz-business" /></template>
<style>
.fm3gxccsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.94 15.633h30.12M8.94 32.367v-8.201a3.605 3.605 0 0 1 7.21 0v8.2m15.7.001v-8.201a3.605 3.605 0 0 1 7.21 0v7.29m-18.665.911v-8.201a3.605 3.605 0 0 1 7.21 0v8.2");
}

.it5im0gms {
  cx: 38.5px;
  cy: 38.433px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ja-y9mbes {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.529 38.433a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.301");
}

.ohhfn9bfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 32.69V9.5c0-2.2-1.8-4-4-4h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h23.305");
}

</style>
