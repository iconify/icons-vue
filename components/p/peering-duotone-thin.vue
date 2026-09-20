<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bzomfeb_l"/><path class="fckjgnb-a"/><path class="v4maambii"/><path class="flq2w3bwj"/><path class="aasy10bhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:peering-duotone-thin" /></template>
<style>
.aasy10bhn {
  d: path("M15.5 18.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.bzomfeb_l {
  fill: currentColor;
  d: path("M2.5 5.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fckjgnb-a {
  fill: currentColor;
  d: path("M15.5 18.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.flq2w3bwj {
  d: path("m9.5 9.5 5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4maambii {
  d: path("M2.5 5.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
