<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibbylvmnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:surf-booties" /></template>
<style>
.ibbylvmnm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 2.75H4Q1.75 2.75 1.75 5v.5q0 .815.504 1.421q-.004.04-.004.079v11.5q0 2.25 2.25 2.25h4q2.75 0 2.75-2.75q0-1.189-1.061-2.641Q9.25 14.075 9.25 13V7q0-.039-.004-.079q.504-.606.504-1.421V5q0-2.25-2.25-2.25m11 0H15q-2.25 0-2.25 2.25v.5q0 .815.504 1.421q-.004.04-.004.079v11.5q0 2.25 2.25 2.25h4q2.75 0 2.75-2.75q0-1.189-1.061-2.641q-.939-1.284-.939-2.359V7q0-.039-.004-.079q.504-.606.504-1.421V5q0-2.25-2.25-2.25M3.75 18.5V7.738q.122.012.25.012h3.5q.128 0 .25-.012V13q0 1.565 1.228 3.245q.772 1.056.772 1.755q0 1.25-1.25 1.25h-4q-.75 0-.75-.75m11 0V7.738q.122.012.25.012h3.5q.128 0 .25-.012V13q0 1.565 1.228 3.245q.772 1.056.772 1.755q0 1.25-1.25 1.25h-4q-.75 0-.75-.75");
}

</style>
