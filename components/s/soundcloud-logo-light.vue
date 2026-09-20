<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m1aidgfoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:soundcloud-logo-light" /></template>
<style>
.m1aidgfoh {
  fill: currentColor;
  d: path("M22 120v48a6 6 0 0 1-12 0v-48a6 6 0 0 1 12 0m26-30a6 6 0 0 0-6 6v96a6 6 0 0 0 12 0V96a6 6 0 0 0-6-6m32-8a6 6 0 0 0-6 6v104a6 6 0 0 0 12 0V88a6 6 0 0 0-6-6m32-32a6 6 0 0 0-6 6v136a6 6 0 0 0 12 0V56a6 6 0 0 0-6-6m109.06 57.88A78 78 0 0 0 144 42a6 6 0 0 0 0 12a65.75 65.75 0 0 1 65.67 59.33a6 6 0 0 0 4.83 5.29A34 34 0 0 1 208 186h-64a6 6 0 0 0 0 12h64a46 46 0 0 0 13.06-90.12");
}

</style>
