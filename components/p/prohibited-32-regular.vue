<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gjf23uc9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-32-regular" /></template>
<style>
.gjf23uc9r {
  fill: currentColor;
  d: path("M6.837 23.749A11.95 11.95 0 0 1 4 16C4 9.373 9.373 4 16 4c2.954 0 5.658 1.067 7.749 2.837zm1.414 1.414L25.163 8.251A11.95 11.95 0 0 1 28 16c0 6.627-5.373 12-12 12a11.95 11.95 0 0 1-7.749-2.837M2 16c0 7.732 6.268 14 14 14s14-6.268 14-14S23.732 2 16 2S2 8.268 2 16");
}

</style>
