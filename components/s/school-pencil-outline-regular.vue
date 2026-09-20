<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rxedw8b6o"/><path class="iq9in6bpg"/><path class="wsj78vmsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:school-pencil-outline-regular" /></template>
<style>
.iq9in6bpg {
  d: path("m7 16 -3 3h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rxedw8b6o {
  d: path("m7 16 9 -9 3 3 -9 9Z");
}

.wsj78vmsl {
  d: path("m14 9 3 3");
}

</style>
