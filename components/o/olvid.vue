<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ni_kq3egb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:olvid" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ni_kq3egb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.743 24c0-6.588-5.155-11.929-11.743-11.929S12.071 17.411 12.071 24c0 4.484 2.475 8.388 6.133 10.426c-1.386 1.535-3.51 3.439-5.717 3.722c9.093 1.293 16.048-.823 20.34-6.123c1.802-2.227 2.916-4.935 2.916-8.025");
}

</style>
