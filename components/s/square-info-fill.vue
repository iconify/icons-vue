<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2xjnhbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-info-fill" /></template>
<style>
.n2xjnhbhu {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm10 2a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm1 4a1 1 0 0 0-2 0v5a1 1 0 0 0 2 0Z");
}

</style>
