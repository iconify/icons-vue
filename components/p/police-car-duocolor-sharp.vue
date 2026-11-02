<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="txp_okbgk"/><path class="ymy1k3bga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-car-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.txp_okbgk {
  stroke-opacity: 0.4;
  d: path("M4 18v-6l2-4h12l2 4v6zm2 0h2v2H6Zm10 0h2v2h-2ZM3 12h18");
}

.ymy1k3bga {
  d: path("M11 8V6h2v2m-2 0h2M7 5h1m8 0h1M8 15h.01M16 15h.01");
}

</style>
