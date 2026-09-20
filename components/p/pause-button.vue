<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w2vml8clc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:pause-button" /></template>
<style>
.w2vml8clc {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M36.57 96h18.29V32H36.57zm36.57-64v64h18.29V32z");
}

</style>
