<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0peqsbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off-fill" /></template>
<style>
.m0peqsbue {
  fill: currentColor;
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414L17.586 18H6a3 3 0 0 1-3-3V6c0-.696.239-1.367.681-1.904L2.293 2.707a.999.999 0 1 1 1.414-1.414M20 14.757L8.243 3H18a3 3 0 0 1 3 3v9q0 .345-.077.68ZM9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
