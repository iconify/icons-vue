<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rmjtaxb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:navigation-play-16-regular" /></template>
<style>
.rmjtaxb4d {
  fill: currentColor;
  d: path("M11.5 6a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-.743 2.572a.5.5 0 0 0-.757.429v2.994a.5.5 0 0 0 .757.429l2.5-1.497a.5.5 0 0 0 0-.858zM6.023 11q.047.517.185 1H2.5a.5.5 0 0 1 0-1zm1.235-4a5.5 5.5 0 0 0-.656 1H2.5a.5.5 0 0 1 0-1zM13.5 3a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1z");
}

</style>
