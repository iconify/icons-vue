<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="et3szacfo"/><path class="b75z21bch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parcel-locker-sharp" /></template>
<style>
.b75z21bch {
  d: path("M14.5 5.25h4.25v4.5H14.5z");
}

.et3szacfo {
  d: path("M2.75 2.75h18.5v18.5H2.75zm9.25 0v18.5M2.75 9H12m-9.25 6H12m0-2.25h9.25m-11.75-7v.5m0 5.5v.5m0 5.5v.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
