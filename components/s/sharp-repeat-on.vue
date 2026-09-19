<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcmpggb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-repeat-on" /></template>
<style>
.qcmpggb4q {
  fill: currentColor;
  d: path("M21 1H3c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m-2 18H7v3l-4-4l4-4v3h10v-4h2zm-2-9V7H7v4H5V5h12V2l4 4z");
}

</style>
