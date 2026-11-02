<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmt5tcc-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-fill" /></template>
<style>
.xmt5tcc-m {
  fill: currentColor;
  d: path("M4.106 5.553C4.643 4.478 5.652 3.001 7 3h10c1.348.001 2.357 1.478 2.894 2.553l1 2c.07.139.106.292.106.447v10a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V8c0-.155.036-.308.106-.447ZM5 18a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V9H5Z");
}

</style>
