<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ww69jzber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-28-filled" /></template>
<style>
.ww69jzber {
  fill: currentColor;
  d: path("M3 6.75A3.75 3.75 0 0 1 6.75 3h6.5v10.25H3zm0 8v6.5A3.75 3.75 0 0 0 6.75 25h6.5V14.75zM14.75 25h6.5A3.75 3.75 0 0 0 25 21.25v-6.5H14.75zM25 13.25v-6.5A3.75 3.75 0 0 0 21.25 3h-6.5v10.25z");
}

</style>
