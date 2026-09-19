<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o71_oroit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-upload-file" /></template>
<style>
.o71_oroit {
  fill: currentColor;
  d: path("M14 2H4v20h16V8zm-1 13v4h-2v-4H8l4.01-4L16 15zm0-6V3.5L18.5 9z");
}

</style>
