<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke-t8hb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-ad-24-filled" /></template>
<style>
.ke-t8hb2w {
  fill: currentColor;
  d: path("M6.25 3A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3zm0 16.5a1.75 1.75 0 0 1-1.75-1.75V8.5h15v9.25a1.75 1.75 0 0 1-1.75 1.75zm.5-9.5a.75.75 0 0 0-.75.75v5c0 .414.336.75.75.75h5a.75.75 0 0 0 .75-.75v-5a.75.75 0 0 0-.75-.75zm.75 5v-3.5H11V15z");
}

</style>
