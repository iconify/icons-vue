<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><circle class="b5s2zlb_d"/><circle class="wdvn5vpwe"/><path class="tjp3z8b0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tax-return-sharp" /></template>
<style>
.b5s2zlb_d {
  cx: 8.5px;
  cy: 7.5px;
  r: 1.5px;
}

.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.tjp3z8b0t {
  d: path("m15 7l-6 7.5M8.25 18h7.5");
}

.wdvn5vpwe {
  cx: 15.5px;
  cy: 14px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
