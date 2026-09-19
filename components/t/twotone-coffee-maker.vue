<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urv1__b3d"/><path class="jlu93diqf"/><circle class="hedj3bbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-coffee-maker" /></template>
<style>
.hedj3bbrm {
  cx: 13px;
  cy: 9px;
  r: 1px;
  fill: currentColor;
}

.jlu93diqf {
  fill: currentColor;
  d: path("M9 7h8c.55 0 1-.45 1-1V4h2V2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h14v-2h-4.03A4.97 4.97 0 0 0 18 16v-5H8v5c0 1.64.81 3.09 2.03 4H6V4h2v2c0 .55.45 1 1 1m1 9v-3h6v3c0 1.65-1.35 3-3 3s-3-1.35-3-3");
}

.urv1__b3d {
  fill: currentColor;
  d: path("M13 19c1.65 0 3-1.35 3-3v-3h-6v3c0 1.65 1.35 3 3 3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
