<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="d223d_x9q"/><path class="zrdou8b0n"/><path class="uxy9sxbfx"/><path class="wgmfnvzml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tokenizer-outline-regular" /></template>
<style>
.d223d_x9q {
  d: path("M3 12h6");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uxy9sxbfx {
  d: path("M3 19h10");
}

.wgmfnvzml {
  d: path("M16 19h5");
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
