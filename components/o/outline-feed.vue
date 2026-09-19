<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="garwhmtap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-feed" /></template>
<style>
.garwhmtap {
  fill: currentColor;
  d: path("M16 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V8zm3 16H5V5h10v4h4zM7 17h10v-2H7zm5-10H7v2h5zm-5 6h10v-2H7z");
}

</style>
