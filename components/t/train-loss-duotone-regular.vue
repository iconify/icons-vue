<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gb7yzvvzz"/><path class="j2i1hfbst"/><path class="qe97cg-lx"/><path class="ea0o9gbbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:train-loss-duotone-regular" /></template>
<style>
.ea0o9gbbj {
  d: path("m5 6 6 6 4 4h4");
}

.gb7yzvvzz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j2i1hfbst {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 6 6 6 4 4h4");
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

</style>
