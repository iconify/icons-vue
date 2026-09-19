<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sw00bb7lb"/><rect class="j3s9ivbxi"/><path class="fu0aa9pky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thai-dict" /></template>
<style>
.fu0aa9pky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.646 20v8m9.21-8h5.3m-2.65 8v-8m-4.172 5.317v.033a2.65 2.65 0 0 1-2.65 2.65h0a2.65 2.65 0 0 1-2.65-2.65v-2.7a2.65 2.65 0 0 1 2.65-2.65h0a2.65 2.65 0 0 1 2.65 2.65v.033M12.844 28v-8h1.8a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5z");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.sw00bb7lb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.505 37.504a7 7 0 0 1-.261.005H5.756q-.132 0-.261-.005m0-5.956a8 8 0 0 1 .26-.004h36.489q.132 0 .26.004m0-15.097a7 7 0 0 1-.26.005H5.756q-.132 0-.26-.005m-.001-5.955q.13-.005.26-.005h36.489q.132 0 .26.005");
}

</style>
