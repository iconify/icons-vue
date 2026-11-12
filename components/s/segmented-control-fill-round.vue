<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqlknbcxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:segmented-control-fill-round" /></template>
<style>
.pqlknbcxd {
  fill: currentColor;
  d: path("M2 10a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19H7a5 5 0 0 1-5-5Zm2 0v4a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3v-4a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3m1 0a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Zm12.01 1a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

</style>
