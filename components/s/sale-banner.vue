<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fgakewkfw"/><path class="jz-otdhhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sale-banner" /></template>
<style>
.fgakewkfw {
  d: path("M12 2.5L19.5 8v13.5h-15V8Zm0 4.25h.01");
}

.jz-otdhhm {
  d: path("M7.5 11.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-3.5.5l4-6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
