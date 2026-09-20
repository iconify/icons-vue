<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mn7qd6v8p"/><path class="k7-o2e8df"/><path fill="url(#SVGW8GOUbNN)" class="s7_cwn4sr"/><defs><linearGradient id="SVGW8GOUbNN" x1="9.029" x2="18.187" y1="15.981" y2="15.981" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qgtsmlbrh"/><stop offset=".76" class="k291d1ptf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mx" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k291d1ptf {
  stop-color: var(--svg-color--1c6ad9, #1c6ad9);
  stop-opacity: 0;
}

.k7-o2e8df {
  fill: var(--svg-color--002f81, #002f81);
  d: path("M16.8 7.406a2.113 2.113 0 0 0-3.7 0l-4.123 7.296c-.753 1.327.185 2.985 1.682 2.985h8.14c1.691 0 2.748-1.872 1.904-3.369z");
}

.mn7qd6v8p {
  fill: var(--svg-color--1977f3, #1977f3);
  d: path("M7.2 7.406a2.113 2.113 0 0 1 3.7 0l5.814 10.28H5.2c-1.691 0-2.748-1.87-1.905-3.368z");
}

.qgtsmlbrh {
  stop-color: var(--svg-color--1c6ad9, #1c6ad9);
}

.s7_cwn4sr {
  d: path("M10.659 17.686h6.055L12 9.348L8.971 14.7c-.748 1.327.19 2.985 1.687 2.985");
}

</style>
