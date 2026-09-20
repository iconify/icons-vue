<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l9fyn0ypz"/><path class="aut-6nhkz"/><path class="ac5nw33zc"/><path class="pt-3kkb2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pipette-duotone-thin" /></template>
<style>
.ac5nw33zc {
  d: path("M9 6a3 3 0 0 1 6 0");
}

.aut-6nhkz {
  d: path("M9 6h6v9l-3 3 -3 -3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9fyn0ypz {
  fill: currentColor;
  d: path("M9 6h6v9l-3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

</style>
