<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pyz3w6bsm"/><path class="lvfjemb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whereby" /></template>
<style>
.lvfjemb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 7.59h16a4.34 4.34 0 0 0 2.05-.44");
}

.pyz3w6bsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 7.59c3.08 0 3.82 6.17 4.62 8.68s6.8 24.58 6.8 24.58S30 17.17 31.54 14.69c2.62-4.11 7.28-7.1 10.12-4.94s2.38 8.3-1.3 15.1c-1.93 3.57-9.14 16-9.14 16L20.45 7.59");
}

</style>
