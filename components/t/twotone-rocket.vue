<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-b8brb2d"/><path class="ttc5z4b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-rocket" /></template>
<style>
.ttc5z4b0r {
  fill: currentColor;
  d: path("M14 11c0-1.1-.9-2-2-2s-2 .9-2 2s.9 2 2 2s2-.9 2-2m-6.02 7.25c-.29-.9-.57-1.94-.76-3L6 16.07v2.98zM12 2s5 2 5 11l2.11 1.41c.56.37.89 1 .89 1.66V22l-5-2H9l-5 2v-5.93c0-.67.33-1.29.89-1.66L7 13c0-9 5-11 5-11m0 2.36S9 6.38 9 13c0 2.25 1 5 1 5h4s1-2.75 1-5c0-6.62-3-8.64-3-8.64m6 14.69v-2.98l-1.22-.81c-.19 1.05-.47 2.1-.76 3z");
}

.z-b8brb2d {
  fill: currentColor;
  d: path("M7.98 18.25c-.29-.9-.57-1.94-.76-3L6 16.07v2.98zM12 4.36S9 6.38 9 13c0 2.25 1 5 1 5h4s1-2.75 1-5c0-6.62-3-8.64-3-8.64M12 13c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2m6 6.05v-2.98l-1.22-.81c-.19 1.05-.47 2.1-.76 3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
