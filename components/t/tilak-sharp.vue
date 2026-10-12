<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gililb_4q"/><path class="fpswrac3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tilak-sharp" /></template>
<style>
.fpswrac3b {
  d: path("M9.25 6.25v4a2.75 2.75 0 0 0 5.5 0v-4M12 6.5V11m-5 6.25l1.625-1.219l1.625 1.219m3.5 0l1.625-1.219L17 17.25");
}

.gililb_4q {
  d: path("M3.75 21.25V12a8.25 8.25 0 0 1 16.5 0v9.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
