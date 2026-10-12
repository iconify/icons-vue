<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bcy734kzt"/><circle class="har4go24q"/><path class="npjwj4b2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:piston-sharp" /></template>
<style>
.bcy734kzt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.75h11v9h-11zm0 3h11M6.5 8h11M12 11.75v4.5");
}

.har4go24q {
  cx: 12px;
  cy: 18.75px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.npjwj4b2p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
