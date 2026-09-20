<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rclmj10lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-right-outline-sharp" /></template>
<style>
.rclmj10lx {
  fill: currentColor;
  d: path("m10 19l-7-7l7-7zm4 0V5l7 7zm1.5-3.625L18.875 12L15.5 8.625z");
}

</style>
