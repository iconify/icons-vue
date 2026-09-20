<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm67rebic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:zoom-out-24-filled" /></template>
<style>
.zm67rebic {
  fill: currentColor;
  d: path("M10 2a8 8 0 0 1 6.162 13.102l4.618 4.618a.75.75 0 0 1-1.06 1.06l-4.618-4.618A8 8 0 1 1 10 2M7.25 9.25a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5z");
}

</style>
