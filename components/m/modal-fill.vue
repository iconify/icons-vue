<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alc8vwbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:modal-fill" /></template>
<style>
.alc8vwbpz {
  fill: currentColor;
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm2 12a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1H5a.997.997 0 0 0-1 1ZM9 7h6a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3");
}

</style>
