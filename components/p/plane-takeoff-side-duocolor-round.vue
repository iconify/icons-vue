<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="obqscbcxp"/><path class="du9jesv4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-side-duocolor-round" /></template>
<style>
.du9jesv4a {
  d: path("m7 13l2-1l-2.5-5A1.12 1.12 0 0 1 7 5.5a1.55 1.55 0 0 1 1.79.29L13 10l6.211-3.106A1.236 1.236 0 0 1 21 8v.764a2 2 0 0 1-1.106 1.789L7.422 16.789a2 2 0 0 1-.894.211H6a1.62 1.62 0 0 1-1.447-.894L4 15c-.46-.919.209-2 1.236-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.obqscbcxp {
  stroke-opacity: 0.4;
  d: path("M3 21h18");
}

</style>
