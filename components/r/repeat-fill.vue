<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycepdvb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:repeat-fill" /></template>
<style>
.ycepdvb3b {
  fill: currentColor;
  d: path("M18.586 7H5a1 1 0 0 0-1 1v3a1 1 0 0 1-2 0V8a3 3 0 0 1 3-3h13.586l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414ZM22 16a3 3 0 0 1-3 3H5.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L5.414 17H19a1 1 0 0 0 1-1v-3a1 1 0 0 1 2 0Z");
}

</style>
