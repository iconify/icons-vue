<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q772ztbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rose-chart" /></template>
<style>
.q772ztbxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.19 3.04zq.7.17 1.37.45q.66.28 1.27.66q.62.37 1.16.84q.55.47 1.02 1.02q.47.54.84 1.16q.38.61.66 1.27q.28.67.45 1.37t-.58.7l-6.13-.01q-.75 0-.75-.75l-.01-6.13q0-.75.7-.58m3.98 10.94zq-.16.49-.39.95q-.23.45-.53.87t-.67.78q-.36.37-.78.67t-.87.53q-.46.23-.95.39t-.49-.59l.01-3.33q0-.75.75-.75l3.33-.01q.75 0 .59.49m-8.32 5.7zq-.66-.19-1.27-.48q-.62-.29-1.18-.69q-.55-.39-1.04-.87q-.48-.49-.87-1.04q-.4-.56-.69-1.18q-.29-.61-.48-1.27q-.18-.66.57-.66l4.86.01q.75 0 .75.75l.01 4.86q0 .75-.66.57m-3.26-9.57zq.14-.41.34-.79t.46-.72q.25-.35.56-.65q.3-.31.65-.56q.34-.26.72-.46t.79-.34q.41-.15.4.6l-.01 2.56q0 .75-.75.75l-2.56.01q-.75.01-.6-.4");
}

</style>
