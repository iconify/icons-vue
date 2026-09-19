<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qolz__bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-where-to-vote" /></template>
<style>
.qolz__bly {
  fill: currentColor;
  d: path("M12 1C7.59 1 4 4.59 4 9c0 5.57 6.96 13.34 7.26 13.67l.74.82l.74-.82C13.04 22.34 20 14.57 20 9c0-4.41-3.59-8-8-8m0 19.47C9.82 17.86 6 12.54 6 9c0-3.31 2.69-6 6-6s6 2.69 6 6c0 3.83-4.25 9.36-6 11.47m-1.53-9.3L8.71 9.4l-1.42 1.42L10.47 14l6.01-6.01l-1.41-1.42z");
}

</style>
