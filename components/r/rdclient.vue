<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kyb4b9bne"/><circle class="ihtc8v-jl"/><path class="lpgk7bc1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rdclient" /></template>
<style>
.ihtc8v-jl {
  cx: 32.45px;
  cy: 30.15px;
  r: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kyb4b9bne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.65 20.05V6.85H4.55v22h14.9V33c0 1 .1 2-2.4 2.1h-2.9a2.15 2.15 0 0 0-2.1 2.1h12");
}

.lpgk7bc1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37 24l-3.9 3.9l3.9 3.9m-8.95-3.25l3.9 3.9l-3.9 3.9m-8.6-7.5h2");
}

</style>
