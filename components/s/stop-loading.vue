<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a88uu03mv"/><path class="pu9x-jbwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stop-loading" /></template>
<style>
.a88uu03mv {
  d: path("M12 2.5A9.5 9.5 0 1 1 2.5 12");
}

.pu9x-jbwp {
  fill: currentColor;
  d: path("M9.25 9.25h5.5v5.5h-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
