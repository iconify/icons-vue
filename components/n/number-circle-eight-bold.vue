<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z0g5dpjxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-circle-eight-bold" /></template>
<style>
.z0g5dpjxz {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m27.6-88.91a36 36 0 1 0-55.2 0a40 40 0 1 0 55.2 0M116 100a12 12 0 1 1 12 12a12 12 0 0 1-12-12m12 68a16 16 0 1 1 16-16a16 16 0 0 1-16 16");
}

</style>
