<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhkjacbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rose-chart-sharp" /></template>
<style>
.fhkjacbyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.19 3.04h0q.7.17 1.37.45q.66.28 1.27.66q.62.37 1.16.84q.55.47 1.02 1.02q.47.54.84 1.16q.38.61.66 1.27q.28.67.45 1.37l.17.7h-.75l-6.13-.01h-.75v-.75l-.01-6.13v-.75zm3.98 10.94h0q-.16.49-.39.95q-.23.45-.53.87t-.67.78q-.36.37-.78.67t-.87.53q-.46.23-.95.39l-.49.16v-.75l.01-3.33v-.75h.75l3.33-.01h.75zm-8.32 5.7h0q-.66-.19-1.27-.48q-.62-.29-1.18-.69q-.55-.39-1.04-.87q-.48-.49-.87-1.04q-.4-.56-.69-1.18q-.29-.61-.48-1.27l-.18-.66h.75l4.86.01h.75v.75l.01 4.86v.75zm-3.26-9.57h0q.14-.41.34-.79t.46-.72q.25-.35.56-.65q.3-.31.65-.56q.34-.26.72-.46t.79-.34l.41-.15l-.01.75l-.01 2.56v.75h-.75l-2.56.01l-.75.01z");
}

</style>
