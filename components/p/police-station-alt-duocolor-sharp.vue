<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="glthtabxm"/><path class="qygvs-stz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-duocolor-sharp" /></template>
<style>
.glthtabxm {
  stroke-opacity: 0.4;
  d: path("M12 6h3v2.625c0 2.063-1.312 3.375-3 4.125c-1.687-.75-3-2.062-3-4.125V6z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qygvs-stz {
  d: path("M3 21h18M5 21V3h14v18m-9 0v-4h4v4");
}

</style>
