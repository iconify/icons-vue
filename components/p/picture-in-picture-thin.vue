<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vn6e_ob5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:picture-in-picture-thin" /></template>
<style>
.vn6e_ob5d {
  fill: currentColor;
  d: path("M216 52H40a12 12 0 0 0-12 12v128a12 12 0 0 0 12 12h176a12 12 0 0 0 12-12V64a12 12 0 0 0-12-12M36 192V64a4 4 0 0 1 4-4h176a4 4 0 0 1 4 4v60h-84a4 4 0 0 0-4 4v68H40a4 4 0 0 1-4-4m180 4h-76v-64h80v60a4 4 0 0 1-4 4");
}

</style>
