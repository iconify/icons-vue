<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mjb9t-b_f"/><path class="uw5kuce7r"/><path class="h66tg3bvx"/><path class="oe-98mb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:windsock-duotone-regular" /></template>
<style>
.h66tg3bvx {
  d: path("M6 6h6l6 6 -6 6H6Z");
}

.mjb9t-b_f {
  fill: currentColor;
  d: path("M6 6h6l6 6 -6 6H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe-98mb0w {
  d: path("M12 6v12");
}

.uw5kuce7r {
  d: path("M3 3v18");
}

</style>
