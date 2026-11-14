<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioaftsxbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-diet" /></template>
<style>
.ioaftsxbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.018 18.75H5.75q-.133.002-.265-.02q-.131-.021-.257-.066q-.125-.044-.241-.11t-.218-.152t-.188-.187t-.152-.217t-.112-.241t-.067-.257l-1.75-7h19l-.606 2.425M5.5 10.5c1-3.5 3.5-5 6.5-5s5.5 1.5 6.5 5M14.75 18l2 2L21 15.75");
}

</style>
