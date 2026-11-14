<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jc9kojdtx"/><path class="enuzerbiy"/><path class="nc_mmcbkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:member-anniversary" /></template>
<style>
.enuzerbiy {
  fill: currentColor;
  d: path("m8.75 6.25l1.176 2.882l3.104.227l-2.378 2.009l.743 3.023L8.75 12.75l-2.645 1.641l.743-3.023L4.47 9.359l3.104-.227Z");
}

.jc9kojdtx {
  d: path("M11.7 20H2.5V4h19v7.2");
}

.nc_mmcbkp {
  d: path("M14.5 15.25h7v6.5h-7Zm0 2.5h7m-5-3.75v1.75m3-1.75v1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
