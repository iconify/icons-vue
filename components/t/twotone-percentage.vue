<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iejt6jbat"/><circle class="il9e6drwv"/><circle class="i_z_5sz_h"/><path class="yay_jkfle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-percentage" /></template>
<style>
.i_z_5sz_h {
  cx: 17px;
  cy: 17px;
  r: 1px;
  fill: currentColor;
  fill-rule: evenodd;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.iejt6jbat {
  fill: currentColor;
  d: path("m18.501 3.5l-15 15.001l1.996 1.996l15-15z");
}

.il9e6drwv {
  cx: 7px;
  cy: 7px;
  r: 1px;
  fill: currentColor;
  fill-rule: evenodd;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yay_jkfle {
  fill: currentColor;
  d: path("M17.003 14a3 3 0 1 1-.006 6a3 3 0 0 1 .006-6M17 16a1 1 0 1 0 0 2a1 1 0 0 0 0-2M7.003 4a3 3 0 1 1-.006 6a3 3 0 0 1 .006-6M7 6a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
