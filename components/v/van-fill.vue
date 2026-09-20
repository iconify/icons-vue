<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fkzcs2hab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:van-fill" /></template>
<style>
.fkzcs2hab {
  fill: currentColor;
  d: path("m254.07 106.79l-45.54-53.06A16 16 0 0 0 196.26 48H32a16 16 0 0 0-16 16v112a16 16 0 0 0 16 16h17a32 32 0 0 0 62 0h50a32 32 0 0 0 62 0h17a16 16 0 0 0 16-16v-64a8 8 0 0 0-1.93-5.21M32 104V64h56v40Zm48 96a16 16 0 1 1 16-16a16 16 0 0 1-16 16m80-96h-56V64h56Zm32 96a16 16 0 1 1 16-16a16 16 0 0 1-16 16m-16-96V64h20.26l34.33 40Z");
}

</style>
