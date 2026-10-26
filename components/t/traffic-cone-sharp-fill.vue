<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="e4yc-o92u"/><path class="lm77aob4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:traffic-cone-sharp-fill" /></template>
<style>
.e4yc-o92u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.0422 21.7127L9.0422 1.7127C9.1691 1.2897 9.5584 1 10 1L14 1C14.4416 1 14.8309 1.2897 14.9578 1.7127L20.9578 21.7127C20.9858 21.8059 21 21.9027 21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22C3 21.9027 3.0142 21.8059 3.0422 21.7127ZM9.344 7.6667L8.744 9.6667L15.256 9.6667L14.656 7.6667L9.344 7.6667ZM7.344 14.3333L6.744 16.3333L17.256 16.3333L16.656 14.3333L7.344 14.3333Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lm77aob4a {
  d: path("M1 22L23 22");
}

</style>
