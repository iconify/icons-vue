<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5hc_9wva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-90-ltr-24-regular" /></template>
<style>
.i5hc_9wva {
  fill: currentColor;
  d: path("M6.75 3a.75.75 0 0 0-.75.75v14.69l-.72-.72a.75.75 0 0 0-1.06 1.06l2 2a.75.75 0 0 0 1.06 0l2-2a.75.75 0 1 0-1.06-1.06l-.72.72V3.75A.75.75 0 0 0 6.75 3m4.28.053l9.496 3.753a.75.75 0 0 1 .104 1.345l-.105.05l-9.5 3.747a.75.75 0 0 1-.643-1.352l.092-.043L13 9.556V5.443l-2.52-.995a.75.75 0 0 1-.454-.876l.031-.097a.75.75 0 0 1 .876-.453zm7.178 4.45L14.5 6.036v2.928zM15.5 12.75a.75.75 0 0 1 1.5 0v5.69l.72-.72a.75.75 0 1 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 1 1 1.06-1.06l.72.72z");
}

</style>
