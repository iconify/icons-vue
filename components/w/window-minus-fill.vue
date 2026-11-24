<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnyzeqghk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-minus-fill" /></template>
<style>
.gnyzeqghk {
  fill: currentColor;
  d: path("M19 21H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3M4 9v9a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V9Zm5 4h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
