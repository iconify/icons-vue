<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4xp8z6hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-fill-sharp" /></template>
<style>
.j4xp8z6hd {
  fill: currentColor;
  d: path("m15.707 4.293l4 4a.999.999 0 1 1-1.414 1.414L17 8.414L12.414 13l2.293 2.293a1 1 0 0 1 0 1.414l-2 2A1 1 0 0 1 12 19H6a1 1 0 0 1-1-1v-6c0-.265.105-.52.293-.707l2-2a1 1 0 0 1 1.414 0L11 11.586L15.586 7l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
