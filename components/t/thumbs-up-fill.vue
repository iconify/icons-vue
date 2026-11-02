<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd8ihccrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-up-fill" /></template>
<style>
.vd8ihccrs {
  fill: currentColor;
  d: path("M8 21.829V8.83A3.01 3.01 0 0 0 10 6V5a3 3 0 1 1 6 0v3a.997.997 0 0 0 1 1h2a3 3 0 0 1 3 3v2a1 1 0 0 1-.051.316l-2 6c-.196.586-.66 1.031-1.203 1.302c-.541.271-1.145.382-1.746.382H9a3 3 0 0 1-1-.171m-2 0A3 3 0 0 1 2 19v-7a3 3 0 0 1 3-3h1Z");
}

</style>
