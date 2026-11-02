<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq6l0acvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-3-2-fill-round" /></template>
<style>
.lq6l0acvi {
  fill: currentColor;
  d: path("M7 5h10a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19H7a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5");
}

</style>
