<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qj77u6b9e"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:six-oclock" /></template>
<style>
.qj77u6b9e {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m2 33.445V50h-4V35.445c-1.19-.693-2-1.969-2-3.445s.81-2.752 2-3.445V6h4v22.555c1.19.693 2 1.969 2 3.445s-.81 2.752-2 3.445");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
