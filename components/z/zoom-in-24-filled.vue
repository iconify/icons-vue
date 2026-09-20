<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e29-n9bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:zoom-in-24-filled" /></template>
<style>
.e29-n9bky {
  fill: currentColor;
  d: path("M10 2a8 8 0 0 1 6.162 13.102l4.618 4.618a.75.75 0 0 1-1.06 1.06l-4.618-4.618A8 8 0 1 1 10 2m0 4.5a.75.75 0 0 0-.75.75v2h-2a.75.75 0 0 0 0 1.5h2v2a.75.75 0 0 0 1.5 0v-2h2a.75.75 0 0 0 0-1.5h-2v-2A.75.75 0 0 0 10 6.5");
}

</style>
