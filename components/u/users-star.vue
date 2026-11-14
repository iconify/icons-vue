<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y25sf5bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:users-star" /></template>
<style>
.y25sf5bxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5c-.6 0-1-.4-1-1c0-3 2.9-5 6.5-5c1.25 0 2.35.25 3.25.75v5.25ZM5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M16 4.5a3.5 3.5 0 0 1 .906 6.881m1.535 4.512l.092.186a1.5 1.5 0 0 0 1.129.821l.205.03a.492.492 0 0 1 .273.838l-.149.145a1.5 1.5 0 0 0-.431 1.328l.035.204a.492.492 0 0 1-.713.519l-.184-.097a1.5 1.5 0 0 0-1.396 0l-.184.097a.492.492 0 0 1-.713-.519l.035-.204a1.5 1.5 0 0 0-.431-1.328l-.149-.145a.492.492 0 0 1 .273-.838l.205-.03a1.5 1.5 0 0 0 1.129-.821l.092-.186a.492.492 0 0 1 .882 0");
}

</style>
