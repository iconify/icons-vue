<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="lxwun53_c"/><path class="jzhurcr0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:steganography-sharp" /></template>
<style>
.jzhurcr0v {
  d: path("m12.25 7.25l3 2.25l3-2.25");
}

.lxwun53_c {
  d: path("m2.75 17.5l4.75-4.75l5.5 5.5m-1-11.5h6.5v5H12z");
}

.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
