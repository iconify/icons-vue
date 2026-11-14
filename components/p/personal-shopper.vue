<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m_o-rebhc"/><path class="fg8blactd"/><path class="bkyl4ww6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:personal-shopper" /></template>
<style>
.bkyl4ww6w {
  d: path("m16.25 16.75l.75-2.5h2l.75 2.5M16 19.5h4");
}

.fg8blactd {
  fill: currentColor;
  d: path("M14.5 16.75h7l-.5 5h-6Z");
}

.m_o-rebhc {
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm-4 14c0-3.855 3.25-6.316 7.513-6.49");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
