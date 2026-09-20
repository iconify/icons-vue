<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mgoqkkb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:person-simple-tai-chi-fill" /></template>
<style>
.mgoqkkb2o {
  fill: currentColor;
  d: path("M96 48a32 32 0 1 1 32 32a32 32 0 0 1-32-32m120 48H40a8 8 0 0 0 0 16h80v28.44l-77.35 69.61A8 8 0 0 0 53.35 222l76.2-68.58L176 173.28V216a8 8 0 0 0 16 0v-48a8 8 0 0 0-4.85-7.35L136 138.72V112h80a8 8 0 0 0 0-16");
}

</style>
