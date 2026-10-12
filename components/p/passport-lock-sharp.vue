<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="bh4biibbp"/><circle class="c3rr-6blb"/><path class="i2aq9xsfi"/></g><path class="kdd0imb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:passport-lock-sharp" /></template>
<style>
.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.c3rr-6blb {
  cx: 12px;
  cy: 10.25px;
  r: 3.75px;
}

.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.i2aq9xsfi {
  d: path("M8.25 10.25h7.5M12 6.5a7.5 7.5 0 0 0 0 7.5");
}

.kdd0imb_o {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 17h5.5v4h-5.5zM16 17v-2.5h3V17");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

.wil2krbkc {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
