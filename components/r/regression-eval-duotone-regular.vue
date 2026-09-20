<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gb7yzvvzz"/><path class="sh3bsvbop"/><path class="qe97cg-lx"/><path class="g0w37q__a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:regression-eval-duotone-regular" /></template>
<style>
.g0w37q__a {
  d: path("m5 16 6 -6h4l4 4");
}

.gb7yzvvzz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.sh3bsvbop {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 16 6 -6h4l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
