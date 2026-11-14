<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmfoj9cwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-float" /></template>
<style>
.qmfoj9cwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 10.5H4v-8h16v8h-6.6m-1.228 4H2.5l1.5-4h8.2m1.2 0H20l1.5 4h-.628m-8.672 5H2.5v-5h9.7m8.7 0h.6v.3M6.75 12.5h.01m3.24 0h.01m7.24 0h.01M7 6.5h10M9.5 17h2.7m2.8-2.5l6.5 3.5l-6.5 3.5Z");
}

</style>
