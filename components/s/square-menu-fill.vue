<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5t3-2bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-menu-fill" /></template>
<style>
.z5t3-2bqo {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm14 2H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m0 4H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m-8 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Z");
}

</style>
