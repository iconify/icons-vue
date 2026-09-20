<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc8a6nbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:man-3-outline" /></template>
<style>
.wc8a6nbhf {
  fill: currentColor;
  d: path("M10.23 21.75v-6.577H8.463V9.289q0-.667.474-1.141t1.141-.475h3.846q.667 0 1.141.475t.475 1.14v5.885h-1.77v6.577zM12 6.308l-1.942-1.942L12 2.423l1.942 1.943z");
}

</style>
