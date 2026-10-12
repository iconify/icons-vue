<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4smjbsyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speed-bump-sharp" /></template>
<style>
.r4smjbsyv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.5h18.5m-15.75 0c1.5-4 3.75-6 6.5-6s5 2 6.5 6Zm4.25 0l2-3.75m1.75 3.75l1.75-3");
}

</style>
