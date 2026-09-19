<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs6yc4b6o"/><path class="bn6ebpb5p"/><path class="qf7_4e_ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-7k" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.gs6yc4b6o {
  fill: currentColor;
  d: path("M5 19h14V5H5zm8-10h1.5v2.25L16.25 9H18l-2.25 3L18 15h-1.75l-1.75-2.25V15H13zM6.5 9H10c.67 0 1.15.65.96 1.29L9.5 15H7.75l1.38-4.5H6.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qf7_4e_ev {
  fill: currentColor;
  d: path("M7.75 15H9.5l1.46-4.71C11.15 9.65 10.67 9 10 9H6.5v1.5h2.63zm6.75-2.25L16.25 15H18l-2.25-3L18 9h-1.75l-1.75 2.25V9H13v6h1.5z");
}

</style>
