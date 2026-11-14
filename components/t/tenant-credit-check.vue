<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf_zburem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tenant-credit-check" /></template>
<style>
.zf_zburem {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13.5a9.5 9.5 0 0 1 4.188-7.876m1.147-.663a9.5 9.5 0 0 1 8.33 0m1.147.663q.462.311.884.675q.422.363.799.773t.703.862q.327.451.598.938q.272.486.484 1.001q.213.515.364 1.051t.238 1.086t.11 1.107M12 13.5L16.5 8m-6 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.75 2.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-1.75 5.75a3.5 3 0 0 1 7 0");
}

</style>
