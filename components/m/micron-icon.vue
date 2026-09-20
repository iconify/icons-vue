<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":135};
const content = `<path class="u4hqz35nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:micron-icon" /></template>
<style>
.u4hqz35nh {
  d: path("M0 109.252h39.346c11.812 0 17.235-4.666 17.235-17.992V63.348C56.58 21.733 76.085 0 113.37 0c19.505 0 34.302 6.936 43.087 20.261C165.622 6.936 179.704 0 199.21 0C236.495 0 256 21.733 256 63.348v71.21h-27.744v-71.21c0-25.684-10.299-38.042-29.047-38.042s-29.047 12.358-29.047 38.042v71.21h-27.744v-71.21c0-25.684-10.298-38.042-29.047-38.042c-18.748 0-29.047 12.358-29.047 38.042V91.26c0 31.107-15.006 43.298-44.978 43.298H0z");
}

</style>
