<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7pgc_e7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-double-fill" /></template>
<style>
.i7pgc_e7m {
  fill: currentColor;
  d: path("M19 8a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

</style>
