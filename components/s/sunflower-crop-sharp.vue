<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cc-u7nn_g"/><circle class="oz-irh__q"/><path class="npjcodbao"/><path class="of6ojcbzg"/><path class="m4im48u9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sunflower-crop-sharp" /></template>
<style>
.cc-u7nn_g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.18 3.11l.39.73l.18.36l.34-.22l.7-.45l.34-.21l-.02.4l-.04.83l-.02.4l.4-.02l.83-.04l.4-.01l-.21.33l-.45.7l-.22.34l.36.18l.73.39l.36.18l-.36.18l-.73.39l-.36.18l.22.34l.45.7l.21.34l-.4-.02l-.83-.04l-.4-.02l.02.4l.04.83l.02.4l-.34-.21l-.7-.45l-.34-.22l-.18.36l-.39.73l-.18.36l-.18-.36l-.39-.73l-.18-.36l-.34.22l-.7.45l-.33.21l.01-.4l.04-.83l.02-.4l-.4.02l-.83.04l-.4.02l.21-.34l.45-.7l.22-.34l-.36-.18l-.73-.39l-.36-.18l.36-.18l.73-.39l.36-.18l-.22-.34l-.45-.7l-.21-.33l.4.01l.83.04l.4.02l-.02-.4l-.04-.83l-.02-.4l.34.21l.7.45l.34.22l.18-.36l.39-.73l.18-.36z");
}

.m4im48u9l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 11.25v10m-8.5-8v8m-3.75 0h18.5M15 17c.5-2 2-3 4.25-3c-.5 2-2 3-4.25 3Z");
}

.npjcodbao {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.69 7.05l.32.51l.19.3l.32-.13l.57-.23l.32-.13l-.02.35l-.05.61l-.02.35l.34.08l.59.15l.34.09l-.22.26l-.4.47l-.22.27l.22.27l.4.47l.22.26l-.34.09l-.59.15l-.34.08l.02.35l.05.61l.02.35l-.32-.13l-.57-.23l-.32-.13l-.19.3l-.32.51l-.19.3l-.19-.3l-.32-.51l-.19-.3l-.32.13l-.57.23l-.32.13l.02-.35l.05-.61l.02-.35l-.34-.08l-.59-.15l-.34-.09l.22-.26l.4-.47l.22-.27l-.22-.27l-.4-.47L3.41 9l.34-.09l.59-.15l.34-.08l-.02-.35l-.05-.61l-.02-.35l.32.13l.57.23l.32.13l.19-.3l.32-.51l.19-.3z");
}

.of6ojcbzg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 10h.01");
}

.oz-irh__q {
  cx: 15px;
  cy: 7px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
