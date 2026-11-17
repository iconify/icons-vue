<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm0tpbzpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-expand-fill" /></template>
<style>
.vm0tpbzpf {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm11 1a1 1 0 0 0 0 2h3v3a1 1 0 0 0 2 0V7a1 1 0 0 0-1-1Zm-2 12a1 1 0 0 0 0-2H8v-3a1 1 0 0 0-2 0v4a1 1 0 0 0 1 1Z");
}

</style>
