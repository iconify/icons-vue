<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qxexlwsii"/><path class="hekbvnb5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-clock-corner-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hekbvnb5z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3L3 6l4 2l2 4zM7 8l1-1m4 10a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

.qxexlwsii {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12.949 3.316l-3 9a1 1 0 0 1-1.843.131L6.255 8.745L2.553 6.894a1 1 0 0 1 .131-1.843l9-3a1.001 1.001 0 0 1 1.265 1.265");
}

</style>
