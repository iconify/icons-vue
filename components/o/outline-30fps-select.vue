<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_5giz3zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-30fps-select" /></template>
<style>
.d_5giz3zl {
  fill: currentColor;
  d: path("M4 4v2h5v2H5v2h4v2H4v2h5c1.1 0 2-.9 2-2v-1.5c0-.83-.17-1.5-1-1.5c.83 0 1-.67 1-1.5V6c0-1.1-.9-2-2-2zm14 0c1.1 0 2 .9 2 2v6c0 1.1-.9 2-2 2h-3c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2zm0 2h-3v6h3zM5 22H3v-5h2zm4 0H7v-5h2zm4 0h-2v-5h2zm8 0h-6v-5h6z");
}

</style>
