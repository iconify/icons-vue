<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyw1ad8sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-view-comfy" /></template>
<style>
.wyw1ad8sz {
  fill: currentColor;
  d: path("M2 4v16h20V4zm2 2h16v5H4zm0 12v-5h4v5zm6 0v-5h10v5z");
}

</style>
