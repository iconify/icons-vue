<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hsyb-9blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:red-circle" /></template>
<style>
.hsyb-9blz {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M126.71 64c0 34.63-28.07 62.71-62.71 62.71c-34.63 0-62.71-28.08-62.71-62.71C1.29 29.36 29.37 1.29 64 1.29c34.64 0 62.71 28.07 62.71 62.71");
}

</style>
