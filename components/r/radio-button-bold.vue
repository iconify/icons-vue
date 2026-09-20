<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yg15ikxad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:radio-button-bold" /></template>
<style>
.yg15ikxad {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m0-140a56 56 0 1 0 56 56a56.06 56.06 0 0 0-56-56m0 88a32 32 0 1 1 32-32a32 32 0 0 1-32 32");
}

</style>
