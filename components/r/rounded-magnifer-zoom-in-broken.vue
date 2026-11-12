<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zbh99ubxk"/><path class="yewbpls5v"/><path class="kz1lj24gh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifer-zoom-in-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kz1lj24gh {
  d: path("M6.5 3.20404C7.82378 2.43827 9.36071 2 11 2C15.9706 2 20 6.02944 20 11C20 15.9706 15.9706 20 11 20C6.02944 20 2 15.9706 2 11C2 9.36071 2.43827 7.82378 3.20404 6.5");
}

.yewbpls5v {
  d: path("M21.4094 21.4094C21.636 21.1828 21.7493 21.0695 21.812 20.9748C22.1793 20.4202 21.99 19.6699 21.4036 19.3559C21.3035 19.3023 21.15 19.2563 20.843 19.1643C20.5075 19.0638 20.3398 19.0136 20.2218 19.0038C19.5268 18.9466 18.9466 19.5268 19.0038 20.2218C19.0136 20.3398 19.0638 20.5076 19.1643 20.843C19.2563 21.15 19.3023 21.3035 19.3559 21.4036C19.6699 21.99 20.4202 22.1793 20.9748 21.812C21.0695 21.7493 21.1828 21.636 21.4094 21.4094Z");
}

.zbh99ubxk {
  d: path("M9 11H11M11 11H13M11 11V13M11 11V9");
}

</style>
