<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hkrtyhkex"/><path class="ymy1k3bga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-car-duocolor-round" /></template>
<style>
.hkrtyhkex {
  stroke-opacity: 0.4;
  d: path("M12 18H6a2 2 0 0 1-2-2v-4l1-2c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2v4a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 12h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ymy1k3bga {
  d: path("M11 8V6h2v2m-2 0h2M7 5h1m8 0h1M8 15h.01M16 15h.01");
}

</style>
