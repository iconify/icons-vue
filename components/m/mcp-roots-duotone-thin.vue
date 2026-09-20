<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e9f2j2cvb"/><path class="kite7sbte"/><path class="bn_pu6j-z"/><path class="t5pp52bpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-roots-duotone-thin" /></template>
<style>
.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.e9f2j2cvb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kite7sbte {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 13 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t5pp52bpq {
  d: path("m9 13 3 3 3 -3");
}

</style>
