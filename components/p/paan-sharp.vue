<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="irsfa4b-v"/><path class="t15as6r0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paan-sharp" /></template>
<style>
.irsfa4b-v {
  d: path("M12 7.5c-1.75-2.75-7.75-3-7.75 2.5c0 3.75 2.75 5.75 5.25 7.75l1.818 1.455L12 21.25l.682-2.045L14.5 17.75c2.5-2 5.25-4 5.25-7.75c0-5.5-6-5.25-7.75-2.5Z");
}

.t15as6r0e {
  d: path("M12 7.5V4.75L13.75 3M12 10.25V17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
