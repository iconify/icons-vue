<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j0f0sgb5u"/><circle class="nk2ff0_eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:os-maps" /></template>
<style>
.j0f0sgb5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.003 6.843c-.142 1.695-2.744 32.522-2.91 34.488a1.57 1.57 0 0 1-2.88.966c-.815-1.103-8.514-13.074-8.514-13.074L9.355 27.556a1.416 1.416 0 0 1-.61-2.671l28.68-19.401c1.525-1.032 2.719-.337 2.578 1.359");
}

.nk2ff0_eh {
  cx: 30.722px;
  cy: 20.25px;
  r: 2.941px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
