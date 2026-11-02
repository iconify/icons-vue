<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-w_25b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-alt-fill" /></template>
<style>
.j-w_25b4j {
  fill: currentColor;
  d: path("M17.949 17.684c.13.392.182.805.152 1.217c-.054.772-.399 1.601-1.111 1.98c-.449.24-.983.24-1.437.013L12 19.118l-3.553 1.776a1.56 1.56 0 0 1-1.437-.013c-.712-.379-1.057-1.208-1.111-1.98a3.1 3.1 0 0 1 .152-1.217l4-12a2.055 2.055 0 0 1 3.898 0Z");
}

</style>
