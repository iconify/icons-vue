<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vzch47bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:power-fill" /></template>
<style>
.vzch47bkz {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104 104 0 0 0 128 24m-8 40a8 8 0 0 1 16 0v64a8 8 0 0 1-16 0Zm8 144A80 80 0 0 1 83.55 61.48a8 8 0 1 1 8.9 13.29a64 64 0 1 0 71.1 0a8 8 0 1 1 8.9-13.29A80 80 0 0 1 128 208");
}

</style>
