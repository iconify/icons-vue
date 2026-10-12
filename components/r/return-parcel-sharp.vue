<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr2x1-bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:return-parcel-sharp" /></template>
<style>
.lr2x1-bgr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 10.25h12.5v11H2.75zm6.25 0v3m11.5 2v-10h-10M12.75 3L10.5 5.25l2.25 2.25");
}

</style>
