<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt5sn12nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safety-vest-sharp" /></template>
<style>
.bt5sn12nq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.04 3.59l2.42 3.82l.54.84l.54-.84l2.42-3.82l.54-.84H18v4.5l.6.8l1.05 1.4l.6.8v11H3.75v-11l.6-.8l1.05-1.4l.6-.8v-4.5h2.5zM12 8.25v13m-8.25-6h16.5");
}

</style>
