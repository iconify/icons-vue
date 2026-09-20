<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dma6ujfzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-align-top-rotate-90-24-filled" /></template>
<style>
.dma6ujfzh {
  fill: currentColor;
  d: path("M21 5.75A2.75 2.75 0 0 0 18.25 3H5.75A2.75 2.75 0 0 0 3 5.75v12.5A2.75 2.75 0 0 0 5.75 21h12.5A2.75 2.75 0 0 0 21 18.25zm-4 1.5v9.5a.75.75 0 0 1-1.5 0v-9.5a.75.75 0 0 1 1.5 0m-4 0v9.5a.75.75 0 0 1-1.5 0v-9.5a.75.75 0 0 1 1.5 0");
}

</style>
