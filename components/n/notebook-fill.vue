<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkx1jm1zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notebook-fill" /></template>
<style>
.gkx1jm1zc {
  fill: currentColor;
  d: path("M6 21a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3ZM18 5H9v14h9a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1m-2 2a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
