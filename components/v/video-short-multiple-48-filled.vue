<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wpzp7-vfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-48-filled" /></template>
<style>
.wpzp7-vfy {
  fill: currentColor;
  d: path("M37.48 9.736a6.24 6.24 0 0 1 2.518 5.014v18.5c0 5.937-4.813 10.75-10.75 10.75h-10.5a6.24 6.24 0 0 1-5.014-2.518q.255.016.514.018h15a8.25 8.25 0 0 0 8.25-8.25v-23a8 8 0 0 0-.017-.514M29.25 4a6.25 6.25 0 0 1 6.25 6.25v23a6.25 6.25 0 0 1-6.25 6.25h-15A6.25 6.25 0 0 1 8 33.25v-23A6.25 6.25 0 0 1 14.25 4zm-8.495 12.103c-1.667-.968-3.755.235-3.755 2.162v6.97c0 1.927 2.088 3.13 3.755 2.163l6.005-3.486c1.66-.963 1.66-3.36 0-4.324z");
}

</style>
