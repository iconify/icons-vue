<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aun8ln3zw"/><path class="xedmbxbzm"/><path class="t6kwsvo7n"/><path class="pg19afyuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sprinkler-outline-regular" /></template>
<style>
.aun8ln3zw {
  d: path("M12 12v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pg19afyuh {
  d: path("M9 8C7 6 5 6 3 7");
}

.t6kwsvo7n {
  d: path("M15 8c2 -2 4 -2 6 -1");
}

.xedmbxbzm {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
