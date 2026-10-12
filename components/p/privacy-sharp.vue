<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mgiids75u"/><path class="nzmsykblt"/><path class="i780oo3eq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:privacy-sharp" /></template>
<style>
.i780oo3eq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.75h.01");
}

.mgiids75u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l6.6 2.45l.652.244l-.002.696v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14l-.002-.696L5.4 5.2Z");
}

.nzmsykblt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 11.75C8.9 10 10.3 9 12 9s3.1 1 4 2.75c-.9 1.75-2.3 2.75-4 2.75s-3.1-1-4-2.75Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
