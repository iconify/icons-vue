<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vawej-f2v"/><path class="huzxyabiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-box-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.huzxyabiw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v18H3Zm9 4l4.5 2.222v5.556L12 17l-4.5-2.222V9.222zM7.5 9.222l4.5 2.222l4.5-2.222M12 11.444V17");
}

.vawej-f2v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 7l4.5 2.222v5.556L12 17l-4.5-2.222V9.222Z");
}

</style>
