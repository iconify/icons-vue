<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f9al-vb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stairs-thin" /></template>
<style>
.f9al-vb4r {
  fill: currentColor;
  d: path("M200 28H56a12 12 0 0 0-12 12v176a12 12 0 0 0 12 12h144a12 12 0 0 0 12-12V40a12 12 0 0 0-12-12m-48 112h52v32h-96v-32Zm4-8v-32h48v32ZM56 36h144a4 4 0 0 1 4 4v52h-52a4 4 0 0 0-4 4v36h-44a4 4 0 0 0-4 4v36H52V40a4 4 0 0 1 4-4m144 184H56a4 4 0 0 1-4-4v-36h152v36a4 4 0 0 1-4 4");
}

</style>
