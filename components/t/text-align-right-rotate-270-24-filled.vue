<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm-0eac0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-right-rotate-270-24-filled" /></template>
<style>
.gm-0eac0u {
  fill: currentColor;
  d: path("M6 19a1 1 0 0 1-1-1V3a1 1 0 0 1 2 0v15a1 1 0 0 1-1 1m12-4a1 1 0 0 1-1-1V3a1 1 0 1 1 2 0v11a1 1 0 0 1-1 1m-7 6a1 1 0 1 0 2 0V3a1 1 0 1 0-2 0z");
}

</style>
