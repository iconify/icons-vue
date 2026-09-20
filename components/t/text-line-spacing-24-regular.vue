<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2iw74bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-line-spacing-24-regular" /></template>
<style>
.y2iw74bjp {
  fill: currentColor;
  d: path("M18.75 13a.75.75 0 0 1 .75.75v5.69l1.22-1.22a.75.75 0 1 1 1.06 1.06l-2.5 2.5a.75.75 0 0 1-.946.094l-.114-.094l-2.5-2.5a.75.75 0 1 1 1.06-1.06L18 19.44v-5.69a.75.75 0 0 1 .75-.75m-8.5 4a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5zm4-6a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5zm4.5-9c.199 0 .39.08.53.22l2.5 2.5a.75.75 0 1 1-1.06 1.06L19.5 4.56v5.69a.75.75 0 0 1-1.5 0V4.56l-1.22 1.22a.75.75 0 1 1-1.06-1.06l2.5-2.5l.114-.094A.75.75 0 0 1 18.75 2m-8.5 3a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5z");
}

</style>
