<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksasmkh2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-small-fill" /></template>
<style>
.ksasmkh2r {
  fill: currentColor;
  d: path("M17 7a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
