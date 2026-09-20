<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><ellipse class="rxsbpt-6p"/><path class="orbk36s6v"/><path class="zzdq5lieg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pay2wash" /></template>
<style>
.orbk36s6v {
  d: path("m14.104 16.274l.1 17.795m4.063 6.123c-.01-5.845-4.033-5.536-4.033-5.536s-4.216-.195-4.086 5.492zm-6.087.096l.041 3.13m3.944-3.13l.04 3.212m1.668-26.02c.215 3.412 4.01 7.37 8.05 7.317c4.119-.036 8.308-2.935 8.335-7.318m-11.75-2.561c.038 2 2.275 2.46 3.537 2.44c1.435 0 3.563-.96 3.496-3.05");
}

.rxsbpt-6p {
  cx: 25.961px;
  cy: 16.243px;
  rx: 11.893px;
  ry: 11.743px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zzdq5lieg {
  d: path("M17.913 17.398c3.556 1.03 3.932-.817 4.513-2.399m7.197.366c1.064 2.138 2.28 3.038 4.757 2.073");
}

</style>
