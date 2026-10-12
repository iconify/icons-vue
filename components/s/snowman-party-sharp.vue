<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gobgdkpxp"/><path class="ecjgov_rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snowman-party-sharp" /></template>
<style>
.ecjgov_rv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.75h.01M12 18h.01");
}

.gobgdkpxp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.18 3.11l1.64 3.28l.18.36h-4l.18-.36l1.64-3.28l.18-.36zm-2.16 3.64h3.96a3 3 0 0 1 .09 4.42a5.25 5.25 0 1 1-4.14 0a3 3 0 0 1 .09-4.42ZM7.38 13.5l-3.75-2.25m12.99 2.25l3.75-2.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
