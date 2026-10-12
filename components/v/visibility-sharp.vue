<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jyf8bur5l"/><circle class="odfkfz5qm"/><path class="ke_4cxbzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:visibility-sharp" /></template>
<style>
.jyf8bur5l {
  d: path("M2.75 10.5c2.5-4 5.75-6 9.25-6s6.75 2 9.25 6c-2.5 4-5.75 6-9.25 6s-6.75-2-9.25-6Z");
}

.ke_4cxbzd {
  d: path("M2.75 20.5h7.5m3.5 0h7.5");
}

.odfkfz5qm {
  cx: 12px;
  cy: 10.5px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
