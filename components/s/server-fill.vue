<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh5rrdbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-fill" /></template>
<style>
.mh5rrdbky {
  fill: currentColor;
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm5 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2ZM2 16a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm5 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
