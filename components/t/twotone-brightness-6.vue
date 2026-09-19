<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhxyjophc"/><path class="pu0t8jbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-brightness-6" /></template>
<style>
.pu0t8jbev {
  fill: currentColor;
  d: path("M20 8.69V4h-4.69L12 .69L8.69 4H4v4.69L.69 12L4 15.31V20h4.69L12 23.31L15.31 20H20v-4.69L23.31 12zm-2 5.79V18h-3.52L12 20.48L9.52 18H6v-3.52L3.52 12L6 9.52V6h3.52L12 3.52L14.48 6H18v3.52L20.48 12zM12 6.5v11c3.03 0 5.5-2.47 5.5-5.5S15.03 6.5 12 6.5");
}

.xhxyjophc {
  fill: currentColor;
  d: path("M18 9.52V6h-3.52L12 3.52L9.52 6H6v3.52L3.52 12L6 14.48V18h3.52L12 20.48L14.48 18H18v-3.52L20.48 12zm-6 7.98v-11c3.03 0 5.5 2.47 5.5 5.5s-2.47 5.5-5.5 5.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
