<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dvebykz8s"/><circle class="rt_37l3dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:nine-oclock" /></template>
<style>
.dvebykz8s {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m6 32h-2.555c-.35.6-.845 1.096-1.445 1.445V38h-4v-2.555A4 4 0 0 1 28.555 34H14v-4h14.555c.35-.6.846-1.096 1.445-1.445V6h4v22.554c.601.35 1.096.845 1.445 1.446H38z");
}

.rt_37l3dj {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: currentColor;
}

</style>
