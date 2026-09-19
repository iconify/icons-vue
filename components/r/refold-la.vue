<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="t-vv0ybmr"/><path class="au-h_ibqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:refold-la" /></template>
<style>
.au-h_ibqo {
  d: path("m44.5 17.678l-8.537-3.869l-4.851 4.967z");
}

.t-vv0ybmr {
  d: path("M37.117 18.284L33.16 31.623l-16.63 4.452l-.713-.705l-.951-23.445l19.627 15.207M15.818 35.37L3.5 23.166l11.972 3.671m12.451-4.796l3.189-3.265");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
