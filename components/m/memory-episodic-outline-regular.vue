<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="be1u5t58a"/><path class="h50arts9k"/><path class="ojg4edcfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-episodic-outline-regular" /></template>
<style>
.be1u5t58a {
  d: path("M6 8h14");
}

.h50arts9k {
  d: path("M6 12h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ojg4edcfp {
  d: path("M6 16h14");
}

.r3faxubne {
  d: path("M4 4v16");
}

</style>
