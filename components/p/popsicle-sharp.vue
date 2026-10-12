<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3y5jbb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:popsicle-sharp" /></template>
<style>
.f3y5jbb9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.25a5.5 5.5 0 0 1 11 0V17h-11v-1.25Zm3.25-.75v6m4.5-6v6M12 17v4.25");
}

</style>
