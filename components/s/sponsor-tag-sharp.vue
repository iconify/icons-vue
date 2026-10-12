<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="emqt89nsg"/><path class="fxhu6xblw"/><path class="c_kh02q3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sponsor-tag-sharp" /></template>
<style>
.c_kh02q3j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.89 10.32l.62 1.37l.14.32l.35.04l1.49.16l.35.04l-.26.23l-1.12 1.01l-.25.23l.07.35l.31 1.47l.07.34l-.3-.18l-1.31-.75l-.3-.17l-.3.17l-1.31.75l-.3.18l.07-.34l.31-1.47l.07-.35l-.25-.23l-1.12-1.01l-.26-.23l.35-.04l1.49-.16l.35-.04l.14-.32l.62-1.37l.14-.32z");
}

.emqt89nsg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 2.75h6v8.5l-1.77 1.77l-6.46 6.46l-1.77 1.77l-1.77-1.77l-4.96-4.96l-1.77-1.77l1.77-1.77l6.46-6.46l1.77-1.77z");
}

.fxhu6xblw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 7h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
