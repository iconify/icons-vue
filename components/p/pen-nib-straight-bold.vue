<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="n3ayukc7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pen-nib-straight-bold" /></template>
<style>
.n3ayukc7e {
  fill: currentColor;
  d: path("M225.92 122.11c-.1-.19-.19-.37-.3-.56L196 68.85V32a20 20 0 0 0-20-20H80a20 20 0 0 0-20 20v36.87l-29.62 52.68a5 5 0 0 0-.3.57a19.89 19.89 0 0 0 1.83 20.71c.09.13.18.25.28.37l86.44 108.29a12 12 0 0 0 18.75 0l86.43-108.29c.1-.12.19-.24.28-.37a19.91 19.91 0 0 0 1.83-20.72M172 36v24H84V36Zm-44 108a10 10 0 1 1 10-10a10 10 0 0 1-10 10m12 65.74v-43.93a34 34 0 1 0-24 0v43.92l-63.17-79.14L79 84h98l26.19 46.59Z");
}

</style>
