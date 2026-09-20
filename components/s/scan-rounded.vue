<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taes1g9yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scan-rounded" /></template>
<style>
.taes1g9yg {
  fill: currentColor;
  d: path("M22 15H2q-.425 0-.712-.288T1 14t.288-.712T2 13h20q.425 0 .713.288T23 14t-.288.713T22 15m-8-6h4l-5-5v4q0 .425.288.713T14 9M6 22q-.825 0-1.412-.587T4 20v-2q0-.425.288-.712T5 17h14q.425 0 .713.288T20 18v2q0 .825-.587 1.413T18 22zM5 11q-.425 0-.712-.288T4 10V4q0-.825.588-1.412T6 2h7.175q.4 0 .763.15t.637.425l4.85 4.85q.275.275.425.638t.15.762V10q0 .425-.288.713T19 11z");
}

</style>
