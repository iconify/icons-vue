<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndtqgwbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mic-external-on" /></template>
<style>
.ndtqgwbyu {
  fill: currentColor;
  d: path("M9.22 7H4.78C4.3 6.47 4 5.77 4 5c0-1.66 1.34-3 3-3s3 1.34 3 3c0 .77-.3 1.47-.78 2M20 2v20h-2V4h-4v18H6v-4H5L4 8h6L9 18H8v2h4V2z");
}

</style>
