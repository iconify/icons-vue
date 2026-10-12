<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ohxdrbbbi"/><path class="ylbyb2b2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:passport-stamp-sharp" /></template>
<style>
.ohxdrbbbi {
  d: path("M3.75 2.75h16.5v18.5H3.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ylbyb2b2e {
  d: path("M9.75 7.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-.9 6.52l5.43-.96l.98-.17l.17.98l.53 2.96l.17.98l-.98.17l-5.43.96l-.98.17l-.17-.98l-.53-2.96l-.17-.98zm1.67 2.24l2.96-.52");
}

</style>
