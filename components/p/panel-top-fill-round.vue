<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv73hovyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-top-fill-round" /></template>
<style>
.xv73hovyv {
  fill: currentColor;
  d: path("M21 16a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5ZM5 16a3.004 3.004 0 0 0 3 3h8a3 3 0 0 0 3-3v-6H5Z");
}

</style>
