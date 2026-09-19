<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="zyxuxxbwx"/><path class="vogl2sbmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-data-store" /></template>
<style>
.vogl2sbmw {
  d: path("m24.39 21.52l5.79-5.883l5.79 5.883m-5.79 9.786h14.023M30.18 15.686v15.62m-18.141-4.837l5.79 5.882l5.79-5.883m-5.789 5.834v-15.62");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zyxuxxbwx {
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
