<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw5gybb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-fill-sharp" /></template>
<style>
.yw5gybb0u {
  fill: currentColor;
  d: path("M10 15v6a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-6H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h7.764l9.789-4.894A1 1 0 0 1 22 3v16a1 1 0 0 1-1.447.894L10.764 15Zm0-2V9H4v4Zm-4 7h2v-5H6Z");
}

</style>
