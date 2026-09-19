<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxu3n4l1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-drive-file-move-rtl" /></template>
<style>
.qxu3n4l1h {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zM12 17l-4-4l4-4v3h4v2h-4z");
}

</style>
