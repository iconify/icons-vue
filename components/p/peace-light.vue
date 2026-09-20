<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dj4ygpbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:peace-light" /></template>
<style>
.dj4ygpbiu {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m90 102a89.44 89.44 0 0 1-13 46.58l-71-49.7V38.2a90.12 90.12 0 0 1 84 89.8m-96-89.8v86.68l-71 49.7A90 90 0 0 1 122 38.2M57.92 184.4L122 139.53v78.27a89.93 89.93 0 0 1-64.08-33.4M134 217.8v-78.27l64.08 44.87A89.93 89.93 0 0 1 134 217.8");
}

</style>
