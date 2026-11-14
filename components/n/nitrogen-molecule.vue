<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnx4c6bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nitrogen-molecule" /></template>
<style>
.vnx4c6bgf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.464 3.464Q12 4.929 12 7q0 1.686.97 2.969l-3 3q-1.284-.97-2.97-.97q-2.072 0-3.536 1.465Q1.999 14.929 2 17q-.001 2.071 1.464 3.536T7 22.001t3.536-1.465T12 17q.001-1.686-.969-2.97l3-3Q15.314 12 17 12q2.071 0 3.536-1.464Q22 9.071 22 7t-1.464-3.536Q19.071 2 17 2t-3.536 1.464");
}

</style>
