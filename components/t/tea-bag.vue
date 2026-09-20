<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="atb763b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tea-bag" /></template>
<style>
.atb763b1j {
  fill: currentColor;
  d: path("M224 160a16 16 0 0 1-16-16V64a56 56 0 0 0-112 0v8H76.53a16.09 16.09 0 0 0-13.72 7.77L42.28 114a16.06 16.06 0 0 0-2.28 8.22V216a16 16 0 0 0 16 16h96a16 16 0 0 0 16-16v-93.78a16.06 16.06 0 0 0-2.28-8.24l-20.53-34.21A16.09 16.09 0 0 0 131.47 72H112v-8a40 40 0 0 1 80 0v80a32 32 0 0 0 32 32a8 8 0 0 0 0-16m-92.53-72L152 122.22V216H56v-93.78L76.53 88H96v48a8 8 0 0 0 16 0V88Z");
}

</style>
