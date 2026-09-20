<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="svv6jr1pu"/><path class="s-q3mjydn"/><path class="x_j9qe7it"/><path class="so0bhmbof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:smart-plug-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-q3mjydn {
  d: path("M9 4v4");
}

.so0bhmbof {
  d: path("M11 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.svv6jr1pu {
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.x_j9qe7it {
  d: path("M15 4v4");
}

</style>
