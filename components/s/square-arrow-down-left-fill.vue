<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3_3fdbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-left-fill" /></template>
<style>
.y3_3fdbcp {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm7 11h4a1 1 0 0 0 0-2h-1.586l4.293-4.293a.999.999 0 1 0-1.414-1.414L10 12.586V11a1 1 0 0 0-2 0v4a1 1 0 0 0 1 1");
}

</style>
