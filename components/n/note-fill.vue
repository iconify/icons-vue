<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si5hqjbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-fill" /></template>
<style>
.si5hqjbrp {
  fill: currentColor;
  d: path("M13.707 20.707A1 1 0 0 1 13 21H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v7c0 .265-.105.52-.293.707ZM15 13a2 2 0 0 0-2 2v4l6-6Z");
}

</style>
