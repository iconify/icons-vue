<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8jwovpxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mushroom-fill-round" /></template>
<style>
.t8jwovpxe {
  fill: currentColor;
  d: path("M20 12h-5v7a3 3 0 1 1-6 0v-7H4a1 1 0 0 1-1-1a9 9 0 0 1 9-9a9 9 0 0 1 9 9a1 1 0 0 1-1 1");
}

</style>
