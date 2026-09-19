<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxk4d9y5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-pause" /></template>
<style>
.dxk4d9y5y {
  fill: currentColor;
  d: path("M6 19h4V5H6zm8-14v14h4V5z");
}

</style>
