<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ycmb5kbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-prohibited-48-regular" /></template>
<style>
.ycmb5kbwd {
  fill: currentColor;
  d: path("M34 24c6.075 0 11 4.925 11 11s-4.925 11-11 11s-11-4.925-11-11s4.925-11 11-11m-5.061 17.83a8.5 8.5 0 0 0 11.89-11.89zM34 26.5a8.5 8.5 0 0 0-6.83 13.562L39.063 28.17A8.46 8.46 0 0 0 34 26.5M25.25 25q.212 0 .417.023a13 13 0 0 0-2.286 2.477H6.75c-.69 0-1.25.56-1.25 1.25v1.242c0 .014.003.088.016.206c.017.162.054.407.13.706a6.2 6.2 0 0 0 1.069 2.216c1.182 1.56 3.71 3.38 9.285 3.38c2.066 0 3.713-.25 5.028-.645c.056.853.194 1.684.406 2.484C19.925 38.755 18.13 39 16 39c-6.175 0-9.522-2.055-11.277-4.37a8.7 8.7 0 0 1-1.501-3.112a8 8 0 0 1-.192-1.05a5 5 0 0 1-.029-.415L3 28.75A3.75 3.75 0 0 1 6.75 25zM16 6a8 8 0 1 1 0 16a8 8 0 0 1 0-16m18 4a6 6 0 1 1 0 12a6 6 0 0 1 0-12M16 8.5a5.5 5.5 0 1 0 0 11a5.5 5.5 0 0 0 0-11m18 4a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7");
}

</style>
