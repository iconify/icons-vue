<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pswhmg6wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:mosque-fill" /></template>
<style>
.pswhmg6wy {
  fill: currentColor;
  d: path("M224 128a23.8 23.8 0 0 0-8 1.38V128c0-41.78-31.07-62.46-53.76-77.56C148.16 41.06 136 33 136 24a8 8 0 0 0-16 0c0 9-12.16 17.06-26.24 26.44C71.07 65.54 40 86.22 40 128v1.38A24 24 0 0 0 8 152v56a8 8 0 0 0 8 8h56a8 8 0 0 0 8-8v-32a16 16 0 0 1 32 0v32a8 8 0 0 0 8 8h16a8 8 0 0 0 8-8v-32a16 16 0 0 1 32 0v32a8 8 0 0 0 8 8h56a8 8 0 0 0 8-8v-56a24 24 0 0 0-24-24M40 200H24v-48a8 8 0 0 1 16 0Zm192 0h-16v-48a8 8 0 0 1 16 0Z");
}

</style>
