<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri96t0v6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tally-2-fill-round" /></template>
<style>
.ri96t0v6a {
  fill: currentColor;
  d: path("M11 19a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
