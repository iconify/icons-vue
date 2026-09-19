<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g75u_vbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-drive-folder-upload" /></template>
<style>
.g75u_vbyt {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zm-9 7v4h-2v-4H8l4.01-4L16 13z");
}

</style>
