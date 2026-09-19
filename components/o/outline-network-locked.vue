<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1a9cdbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-network-locked" /></template>
<style>
.g1a9cdbgz {
  fill: currentColor;
  d: path("M22 16v-.5a2.5 2.5 0 0 0-5 0v.5c-.55 0-1 .45-1 1v4c0 .55.45 1 1 1h5c.55 0 1-.45 1-1v-4c0-.55-.45-1-1-1m-1 0h-3v-.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5zM18 5.83v5.43c.47-.16.97-.26 1.5-.26c.17 0 .33.03.5.05V1L1 20h13v-2H5.83z");
}

</style>
