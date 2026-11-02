<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en9t1ybbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-align-right-fill-round" /></template>
<style>
.en9t1ybbw {
  fill: currentColor;
  d: path("M20 5a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Z");
}

</style>
