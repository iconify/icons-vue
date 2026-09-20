<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zrokgqbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-right-20-filled" /></template>
<style>
.zrokgqbld {
  fill: currentColor;
  d: path("M6 6a4 4 0 1 0 0 8h8a4 4 0 0 0 0-8zm8 6a2 2 0 1 1 0-4a2 2 0 0 1 0 4");
}

</style>
