<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b5syicbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:radio-fill" /></template>
<style>
.b5syicbex {
  fill: currentColor;
  d: path("M216 64H86.51L194.3 31.67a8 8 0 0 0-4.6-15.33l-160 48A8 8 0 0 0 24 72v120a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16V80a16 16 0 0 0-16-16M104 176H64a8 8 0 0 1 0-16h40a8 8 0 0 1 0 16m0-32H64a8 8 0 0 1 0-16h40a8 8 0 0 1 0 16m0-32H64a8 8 0 0 1 0-16h40a8 8 0 0 1 0 16m64 56a32 32 0 1 1 32-32a32 32 0 0 1-32 32");
}

</style>
