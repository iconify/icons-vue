<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="ngs5zqb4k"/><path class="kk0ezbc9j"/></g><g class="y9tr6bcfx"><circle class="d889cvkdz"/><path class="g18g_0bmj"/></g><g class="y9tr6bcfx"><circle class="iukdhybpg"/><path class="o7dp-hb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shareit" /></template>
<style>
.d889cvkdz {
  cx: 10.375px;
  cy: 32.921px;
  r: 6.821px;
}

.g18g_0bmj {
  d: path("M5.65 28.001c-3.57-6.185-.418-18.45 12.376-21.974c-10.207 9.502-8.77 16.268-7.258 20.084");
}

.iukdhybpg {
  cx: 37.625px;
  cy: 32.921px;
  r: 6.821px;
}

.kk0ezbc9j {
  d: path("M30.623 7.69c7.142 0 16.186 8.862 12.842 21.704c-3.126-13.59-9.703-15.73-13.765-16.328");
}

.ngs5zqb4k {
  cx: 24px;
  cy: 9.321px;
  r: 6.821px;
}

.o7dp-hb-c {
  d: path("M35.727 39.472c-3.57 6.185-15.769 9.587-25.218.27c13.333 4.088 18.474-.539 21.023-3.757");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
