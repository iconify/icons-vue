<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGJ2ijce8T)" clip-rule="evenodd" class="oqkmlbwsh"/><path fill="url(#SVGbIh7GLKD)" clip-rule="evenodd" class="v3zvifbsl"/><defs><linearGradient id="SVGJ2ijce8T" x1="3.57" x2="21.096" y1="15.989" y2="8.281" gradientUnits="userSpaceOnUse"><stop class="nk6ojylru"/><stop offset=".782" class="ohmm7omcz"/><stop offset="1" class="pnpu0-_dg"/></linearGradient><linearGradient id="SVGbIh7GLKD" x1="11.225" x2="15.53" y1="14.635" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="hgeb_65ov"/><stop offset="1" class="ddm61obqw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:titan" /></template>
<style>
.ddm61obqw {
  stop-color: var(--svg-color--3a5ef4, #3a5ef4);
}

.ft5dv1b6b {
  fill: none;
}

.hgeb_65ov {
  stop-color: var(--svg-color--05d5ff, #05d5ff);
}

.nk6ojylru {
  stop-color: var(--svg-color--04d9ff, #04d9ff);
}

.ohmm7omcz {
  stop-color: var(--svg-color--445cfe, #445cfe);
}

.oqkmlbwsh {
  fill-rule: evenodd;
  d: path("M18.632 12a6.632 6.632 0 0 1-11.554 4.445c-.464.1-.892.184-1.272.249c-.872.096-2.653-.008-2.798-1.187c-.132-1.073 1.385-2.458 2.368-3.174a6.632 6.632 0 0 1 11.374-4.96c4.644-.745 4.57 1.139 3.948 2.178c-.538.76-1.25 1.457-2.076 2.094q.01.177.01.355M12 16.737a4.7 4.7 0 0 1-2.701-.845a40 40 0 0 0 3.585-1.183l-.862-1.622l-.315.144c-1.04.486-3.862 1.515-6.84 1.74c.47-.433 1.551-1.362 2.485-1.87l.038-.009a4.737 4.737 0 0 1 9.2-2.265q-.85.534-1.749.978l-.494.225l.474 1.859q.93-.431 1.82-.936A4.74 4.74 0 0 1 12 16.737m6.214-7.059a7 7 0 0 0-.306-.693c.394-.043.928-.096 1.2-.11c-.17.183-.473.465-.894.803");
}

.pnpu0-_dg {
  stop-color: var(--svg-color--7269ef, #7269ef);
}

.v3zvifbsl {
  fill-rule: evenodd;
  d: path("M13.421 15.317a1.895 1.895 0 1 0 0-3.79a1.895 1.895 0 0 0 0 3.79m0-.947a.947.947 0 1 0 0-1.895a.947.947 0 0 0 0 1.895");
}

</style>
