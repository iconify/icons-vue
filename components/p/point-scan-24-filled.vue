<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ialruwb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:point-scan-24-filled" /></template>
<style>
.ialruwb2q {
  fill: currentColor;
  d: path("M10.25 2a.75.75 0 0 1 .743.648L11 2.75v4.794A6.25 6.25 0 0 1 16.457 13h4.794a.75.75 0 0 1 .102 1.493l-.102.007h-4.794A6.25 6.25 0 0 1 11 19.956v1.295a.75.75 0 0 1-1.494.102L9.5 21.25v-1.295a6.25 6.25 0 0 1-5.455-5.454H2.75a.75.75 0 0 1-.102-1.494L2.75 13h1.294A6.25 6.25 0 0 1 9.5 7.544V2.75a.75.75 0 0 1 .75-.75m0 5.5q-.381 0-.75.044V13H4.044a6.3 6.3 0 0 0 0 1.5H9.5v5.455a6.3 6.3 0 0 0 1.5 0V14.5h5.456a6.3 6.3 0 0 0 0-1.5H11V7.544a6 6 0 0 0-.75-.044");
}

</style>
