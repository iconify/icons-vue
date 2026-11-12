<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khmnknblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-plus-fill" /></template>
<style>
.khmnknblc {
  fill: currentColor;
  d: path("M20 20a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V7c0-.265.105-.52.293-.707l4-4A1 1 0 0 1 9 2h6c.265 0 .52.105.707.293l4 4A1 1 0 0 1 20 7ZM11 5a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2Zm2 9v-2a1 1 0 0 0-2 0v2H9a1 1 0 0 0 0 2h2v2a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2Z");
}

</style>
