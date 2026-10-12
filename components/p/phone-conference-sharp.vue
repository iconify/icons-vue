<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xy9fq6ykd"/><circle class="c9bd5qgta"/><circle class="b5yof9bmt"/><path class="c8tsrmbgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-conference-sharp" /></template>
<style>
.b5yof9bmt {
  cx: 18.75px;
  cy: 4.25px;
  r: 1.25px;
}

.c8tsrmbgt {
  d: path("m12.25 9.5l.482-2.25h3.536l.482 2.25m-.25 0l.482-2.25h3.536L21 9.5");
}

.c9bd5qgta {
  cx: 14.5px;
  cy: 4.25px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xy9fq6ykd {
  d: path("M5.6 3.25h2.6l.72-.002l.23.682l1.1 3.3l.19.587l-.44.433l-1.6 1.6a12.5 12.5 0 0 0 5.75 5.75l1.6-1.6l.433-.44l.587.19l3.3 1.1l.682.23l-.002.72v4.95H18.4c-8.3 0-15.15-6.85-15.15-15.15V3.25z");
}

</style>
