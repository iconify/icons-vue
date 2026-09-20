<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j_xgkybnr"/><path class="cdika4gid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:mermaid" /></template>
<style>
.cdika4gid {
  fill: var(--svg-color--fff, #fff);
  d: path("M212.818 58.067C175.27 56.46 140.792 79.563 128 114.9c-12.792-35.337-47.27-58.44-84.818-56.833c-1.25 29.795 13.003 58.209 37.635 75.02a46.42 46.42 0 0 1 20.124 38.361v26.563h54.123v-26.563a46.42 46.42 0 0 1 20.119-38.361c24.639-16.805 38.895-45.223 37.635-75.02");
}

.j_xgkybnr {
  fill: var(--svg-color--ff3670, #ff3670);
  d: path("M256 44.19C256 19.8 236.2 0 211.81 0H44.19C19.8 0 0 19.8 0 44.19v167.62C0 236.2 19.8 256 44.19 256h167.62c24.39 0 44.19-19.8 44.19-44.19z");
}

</style>
