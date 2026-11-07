<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgargiblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:newspaper-fill" /></template>
<style>
.lgargiblk {
  fill: currentColor;
  d: path("M8 3h11a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H8ZM6 7v14H5a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3Zm12 0h-6a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2m-6 4a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Zm6 4h-6a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
