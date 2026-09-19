<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx4g48bxm"/><path class="wc-lwza-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-brightness-medium" /></template>
<style>
.qx4g48bxm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M18 9.52V6h-3.52L12 3.52L9.52 6H6v3.52L3.52 12L6 14.48V18h3.52L12 20.48L14.48 18H18v-3.52L20.48 12zM12 18V6c3.31 0 6 2.69 6 6s-2.69 6-6 6");
}

.wc-lwza-e {
  fill: currentColor;
  d: path("M20 8.69V4h-4.69L12 .69L8.69 4H4v4.69L.69 12L4 15.31V20h4.69L12 23.31L15.31 20H20v-4.69L23.31 12zm-2 5.79V18h-3.52L12 20.48L9.52 18H6v-3.52L3.52 12L6 9.52V6h3.52L12 3.52L14.48 6H18v3.52L20.48 12zM12 6v12c3.31 0 6-2.69 6-6s-2.69-6-6-6");
}

</style>
