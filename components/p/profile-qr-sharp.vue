<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b5br8-0fg"/><path class="s8nsc37xh"/><circle class="zkh97bw0b"/><path class="kmixz0bja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:profile-qr-sharp" /></template>
<style>
.b5br8-0fg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h6.5v6.5h-6.5zm12 0h6.5v6.5h-6.5zm-12 12h6.5v6.5h-6.5z");
}

.kmixz0bja {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 21.25h6v-.5c0-1.4-1.6-2-3.25-2s-3.25.6-3.25 2v.5z");
}

.s8nsc37xh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6h.01M18 6h.01M6 18h.01M12 3.75h.01M12 8h.01m-8.26 4h.01M8 12h.01M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zkh97bw0b {
  cx: 18px;
  cy: 14.75px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
