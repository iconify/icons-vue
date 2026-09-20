<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="c4qr3dboa"/><path class="h7bcztycq"/><path class="nf735qztg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:port-forward-outline-regular" /></template>
<style>
.c4qr3dboa {
  d: path("M2 8h10");
}

.h7bcztycq {
  d: path("M12 8v8");
}

.nf735qztg {
  d: path("M12 16h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
