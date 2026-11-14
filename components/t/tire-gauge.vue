<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kkm-ahb6y"/><path class="bn208jb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tire-gauge" /></template>
<style>
.bn208jb_v {
  d: path("M16.5 17.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.kkm-ahb6y {
  d: path("m14.005 4.813l3.182 3.182l-8.132 8.132l-3.182-3.182Zm3.713-.531l-2.122 2.122m-8.132 8.132l-3.182 3.182m9.468-.218a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
