<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9vb0dbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-1-outline-rounded" /></template>
<style>
.b9vb0dbqf {
  fill: currentColor;
  d: path("m12 10.108l-4.246 4.24q-.14.14-.341.153t-.367-.153q-.16-.16-.16-.354t.16-.354l4.389-4.388q.13-.13.267-.184T12 9.015t.298.053t.268.184l4.388 4.388q.14.14.153.342t-.153.366q-.16.16-.354.16t-.354-.16z");
}

</style>
