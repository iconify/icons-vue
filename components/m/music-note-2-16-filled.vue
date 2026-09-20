<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y8sondphq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-note-2-16-filled" /></template>
<style>
.y8sondphq {
  fill: currentColor;
  d: path("M12 5.21v5.058A2 2 0 1 0 13 12V1.925a.8.8 0 0 0-1.07-.754l-6.4 2.286A.8.8 0 0 0 5 4.21v7.057A2 2 0 1 0 6 13V7.351z");
}

</style>
