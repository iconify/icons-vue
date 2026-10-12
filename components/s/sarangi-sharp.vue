<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1x3kbcre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sarangi-sharp" /></template>
<style>
.q1x3kbcre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.92 4.45l.347-.931l.933.341l1.41.51l.939.34l-.339.94l-2.8 7.69a4 4.25 20 1 1-3.29-1.2Zm-.17.47l-1.88-.68m.51 4.44L9.5 8m6.54-1.88l1.88.68m-3.25 3.08l1.88.68");
}

</style>
