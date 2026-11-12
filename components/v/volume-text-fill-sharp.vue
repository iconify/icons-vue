<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3tvse0vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-text-fill-sharp" /></template>
<style>
.h3tvse0vq {
  fill: currentColor;
  d: path("m15.586 9l4.707-4.707A1 1 0 0 1 22 5v14a1.002 1.002 0 0 1-1.707.707L15.586 15H13a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1ZM9 8a1 1 0 0 1 0 2H7v5a1 1 0 0 1-2 0v-5H3a1 1 0 0 1 0-2Z");
}

</style>
