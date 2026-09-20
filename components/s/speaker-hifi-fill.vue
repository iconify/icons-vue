<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t1ivdccni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:speaker-hifi-fill" /></template>
<style>
.t1ivdccni {
  fill: currentColor;
  d: path("M152 160a24 24 0 1 1-24-24a24 24 0 0 1 24 24m56-120v176a16 16 0 0 1-16 16H64a16 16 0 0 1-16-16V40a16 16 0 0 1 16-16h128a16 16 0 0 1 16 16m-92 28a12 12 0 1 0 12-12a12 12 0 0 0-12 12m52 92a40 40 0 1 0-40 40a40 40 0 0 0 40-40");
}

</style>
