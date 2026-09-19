<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw6235bcd"/><path class="h6i3--k-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-double-arrow" /></template>
<style>
.h6i3--k-y {
  fill: currentColor;
  d: path("M8.5 5H4l5 7l-5 7h4.5l5-7z");
}

.yw6235bcd {
  fill: currentColor;
  d: path("M15.5 5H11l5 7l-5 7h4.5l5-7z");
}

</style>
