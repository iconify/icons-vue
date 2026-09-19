<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jq5s0fbpw"/><path class="f-sd7fbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vvsmobil" /></template>
<style>
.f-sd7fbre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.72 27.9l-2.6 8l-2.6-8m12.95 0l-2.6 8l-2.6-8m7.86 7.1c.5.6 1.1.9 2 .9h1.2c1.1 0 2-.9 2-2s-.9-2-2-2h-1.3c-1.1 0-2-.9-2-2s.9-2 2-2h1.2c.9 0 1.5.2 2 .9");
}

.jq5s0fbpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.05 43.934A21.5 21.5 0 1 1 45.496 24h-3.72a17.78 17.78 0 1 0-11.12 16.486z");
}

</style>
