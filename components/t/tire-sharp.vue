<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="ka4pbmzuc"/><circle class="peiq2hfxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tire-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.ka4pbmzuc {
  d: path("M12 6a6 6 0 1 0 0 12a6 6 0 0 0 0-12Zm1.6 4.4l2.54-2.54M10.4 10.4L7.86 7.86m2.54 5.74l-2.54 2.54m5.74-2.54l2.54 2.54");
}

.peiq2hfxm {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
