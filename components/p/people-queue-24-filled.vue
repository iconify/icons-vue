<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur_0p8bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-queue-24-filled" /></template>
<style>
.ur_0p8bvt {
  fill: currentColor;
  d: path("M10.5 6a3 3 0 1 1-6 0a3 3 0 0 1 6 0m-5.75 4A1.75 1.75 0 0 0 3 11.75v4.75a4.5 4.5 0 1 0 9 0v-4.75A1.75 1.75 0 0 0 10.25 10zm6.11 10.854A5.49 5.49 0 0 0 13 16.5v-4.75c0-.665-.236-1.274-.629-1.75h2.379c.966 0 1.75.784 1.75 1.75v4.75a4.5 4.5 0 0 1-5.64 4.354M11.5 6c0 1-.367 1.913-.973 2.614a3 3 0 1 0 0-5.229c.606.702.973 1.616.973 2.615m3.86 14.854A5.49 5.49 0 0 0 17.5 16.5v-4.75c0-.665-.236-1.274-.629-1.75h2.379c.966 0 1.75.784 1.75 1.75v4.75a4.5 4.5 0 0 1-5.64 4.354M16 6c0 1-.367 1.913-.973 2.614a3 3 0 1 0 0-5.229C15.633 4.088 16 5.002 16 6");
}

</style>
