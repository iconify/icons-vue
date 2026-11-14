<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kb-b5_0wk"/><path class="gcui2yj9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rear-window" /></template>
<style>
.gcui2yj9s {
  d: path("M7.25 13.25a5.5 5.5 0 0 1 9.5 0M12 16h.01");
}

.kb-b5_0wk {
  d: path("M6.5 5h11L21 19H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
