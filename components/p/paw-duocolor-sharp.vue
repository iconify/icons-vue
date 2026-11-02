<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y9k696pnq"/><path class="wqx177b_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paw-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wqx177b_i {
  d: path("M12 10c2.5 0 3.6 2.2 5 4c1 1.3 2 2.3 2 4c0 1.3-1.2 2-3 2c-1.5 0-2.5-1-4-1s-2.5 1-4 1c-1.8 0-3-.7-3-2c0-1.7 1-2.7 2-4c1.4-1.8 2.5-4 5-4");
}

.y9k696pnq {
  stroke-opacity: 0.4;
  d: path("M4 10a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
