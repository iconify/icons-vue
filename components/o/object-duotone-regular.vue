<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_ol36b6f"/><path class="w4h8tdb0x"/><path class="k6t-okb_f"/><path class="urk2115hi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:object-duotone-regular" /></template>
<style>
.k6t-okb_f {
  d: path("M9 4 7 6v4l-2 2 2 2v4l2 2");
}

.n_ol36b6f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 4 7 6v4l-2 2 2 2v4l2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.urk2115hi {
  d: path("m15 4 2 2v4l2 2 -2 2v4l-2 2");
}

.w4h8tdb0x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 4 2 2v4l2 2 -2 2v4l-2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
