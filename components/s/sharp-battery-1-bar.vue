<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp3g3ccne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-1-bar" /></template>
<style>
.sp3g3ccne {
  fill: currentColor;
  d: path("M17 4v18H7V4h3V2h4v2zm-2 2H9v12h6z");
}

</style>
