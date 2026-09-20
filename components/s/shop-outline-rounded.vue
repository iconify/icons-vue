<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i68l_qoyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shop-outline-rounded" /></template>
<style>
.i68l_qoyg {
  fill: currentColor;
  d: path("m11.05 17l4.15-2.65q.45-.3.45-.85t-.45-.85L11.05 10q-.5-.325-1.025-.05t-.525.875v5.35q0 .6.525.875T11.05 17M4 21q-.825 0-1.412-.587T2 19V7q0-.425.288-.712T3 6h5V4q0-.825.588-1.412T10 2h4q.825 0 1.413.588T16 4v2h5q.425 0 .713.288T22 7v12q0 .825-.587 1.413T20 21zm0-2h16V8H4zm6-13h4V4h-4zM4 19V8z");
}

</style>
