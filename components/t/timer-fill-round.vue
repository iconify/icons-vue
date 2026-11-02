<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcer7mbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:timer-fill-round" /></template>
<style>
.mcer7mbvx {
  fill: currentColor;
  d: path("M14 2a1 1 0 0 1 0 2h-1v.054a9 9 0 0 1 4.618 1.913l1.675-1.674a.999.999 0 1 1 1.414 1.414l-1.674 1.675A9 9 0 1 1 11 4.054V4h-1a1 1 0 0 1 0-2Zm-3 11a1 1 0 0 0 2 0V9a1 1 0 0 0-2 0Z");
}

</style>
