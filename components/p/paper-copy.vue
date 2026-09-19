<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nrqpvcc4x"/><path class="jo7g3xb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paper-copy" /></template>
<style>
.jo7g3xb3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.284 5.5c-7.297 0-13.213 5.917-13.213 13.215v0c.001 7.297 5.916 13.212 13.213 13.213c7.298 0 13.215-5.915 13.215-13.213v0c0-.812-.075-1.623-.224-2.422H31.707V5.725c-.799-.15-1.61-.224-2.422-.225z");
}

.nrqpvcc4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.929 29.286c0 7.298-5.917 13.214-13.215 13.214H5.501V29.286c0-7.298 5.916-13.214 13.213-13.214S31.93 21.988 31.93 29.286");
}

</style>
