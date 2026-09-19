<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oalacdfvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-week" /></template>
<style>
.oalacdfvx {
  fill: currentColor;
  d: path("M7.33 20H2V4h5.33zM22 20V4h-5.33v16zm-7.33 0V4H9.33v16z");
}

</style>
