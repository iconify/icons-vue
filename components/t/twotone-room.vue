<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxiwu_b_n"/><path class="zs29x6brz"/><circle class="sepm5fbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-room" /></template>
<style>
.sepm5fbik {
  cx: 12px;
  cy: 9px;
  r: 2.5px;
  fill: currentColor;
}

.uxiwu_b_n {
  fill: currentColor;
  d: path("M12 4C9.24 4 7 6.24 7 9c0 2.85 2.92 7.21 5 9.88c2.11-2.69 5-7 5-9.88c0-2.76-2.24-5-5-5m0 7.5a2.5 2.5 0 0 1 0-5a2.5 2.5 0 0 1 0 5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.zs29x6brz {
  fill: currentColor;
  d: path("M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7M7 9c0-2.76 2.24-5 5-5s5 2.24 5 5c0 2.88-2.88 7.19-5 9.88C9.92 16.21 7 11.85 7 9");
}

</style>
