<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="utzb68zav"/><path class="sci58wslm"/><path class="p9otx-o7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-camera-cyber-sharp" /></template>
<style>
.p9otx-o7w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12.25V17H4.75m0-2.25v4.5M18 7.25L19.715 9L18 10.75m1.75-5.25a5 5 0 0 1 0 7");
}

.sci58wslm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9h.01");
}

.utzb68zav {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h12.5v6.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
