<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="enpsf2m7q"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:twelve-thirty" /></template>
<style>
.enpsf2m7q {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m4 30c0 1.477-.81 2.753-2 3.445V58h-4V38.51l-2-.533l.925-3.447A3.96 3.96 0 0 1 28 32c0-1.479.81-2.753 2-3.445V26h1.213l2.951-11L38 16.027L34.538 28.93A3.98 3.98 0 0 1 36 32");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
