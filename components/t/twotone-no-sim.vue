<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgf9r-bmq"/><path class="pxu9hqb9x"/><path class="xgyps3fkn"/><path class="ij4dwobwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-no-sim" /></template>
<style>
.ij4dwobwl {
  fill: currentColor;
  d: path("M10.84 5H17v9.11l2 2V5c0-1.1-.9-2-2-2h-6.99L7.95 5.06l1.41 1.41z");
}

.pxu9hqb9x {
  fill: currentColor;
  d: path("M3.79 3.74L2.38 5.15l2.74 2.74l-.12.12V19c0 1.1.9 2 2 2h10c.35 0 .68-.1.97-.26l1.88 1.88l1.41-1.41zM7 19V9.77L16.23 19z");
}

.xgyps3fkn {
  fill: currentColor;
  d: path("M10.84 5L9.36 6.47L17 14.11V5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zgf9r-bmq {
  fill: currentColor;
  d: path("M7 19h9.23L7 9.77z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
