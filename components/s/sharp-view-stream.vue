<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1jb6ibdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-stream" /></template>
<style>
.d1jb6ibdc {
  fill: currentColor;
  d: path("M3 19v-6h18v6zM3 5v6h18V5z");
}

</style>
