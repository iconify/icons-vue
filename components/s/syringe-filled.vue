<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vi91yw2-z"/><path class="smcgo1b8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:syringe-filled" /></template>
<style>
.smcgo1b8m {
  fill: currentColor;
  d: path("m13.591 8.641l1.768 1.768l-4.42 4.419l-1.767-1.767Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vi91yw2-z {
  d: path("m14.121 5.636l4.243 4.243l-7.425 7.424l-4.242-4.242Zm-1.06-1.061l6.364 6.364m-.707-5.657l-2.475 2.475m1.06-3.889l2.829 2.829M8.818 15.182l-3.536 3.536");
}

</style>
