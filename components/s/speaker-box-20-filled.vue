<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t2fv80kpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-box-20-filled" /></template>
<style>
.t2fv80kpt {
  fill: currentColor;
  d: path("M4 5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3zm6 5a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-3 2a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3-5a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
