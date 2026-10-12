<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jwk-cd49x"/><path class="j0f5vuboa"/><path class="oxrsgf2dh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mood-tracker-sharp" /></template>
<style>
.j0f5vuboa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01m4.99 0h.01");
}

.jwk-cd49x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.25h16.5v16H3.75zM8 2.75v4.5m8-4.5v4.5");
}

.oxrsgf2dh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.75 15.5l1.352 1.75h3.796l1.352-1.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
