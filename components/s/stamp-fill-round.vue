<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf1evobxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stamp-fill-round" /></template>
<style>
.pf1evobxl {
  fill: currentColor;
  d: path("M9 11V8.38a3.828 3.828 0 0 1 5.601-5.189A3.83 3.83 0 0 1 15 8.38V11h3a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-1a3 3 0 0 1 3-3Zm10 9a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

</style>
