<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gv4y775vu"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:one-thirty" /></template>
<style>
.gv4y775vu {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m4 30c0 1.477-.81 2.752-2 3.445V58h-4V36.857L28.857 38L26 35.145l2.142-2.143A4 4 0 0 1 28 32c0-1.477.81-2.752 2-3.445V26h4v1.144L43.143 18L46 20.859L35.858 31c.084.321.142.652.142 1");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
