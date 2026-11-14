<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm7-febuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sitemap" /></template>
<style>
.wm7-febuq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 2.25h-1q-3.25 0-3.25 3.25q0 3.122 3 3.245v3.005H6.5q-2.25 0-2.25 2.25v1.331q-.873.196-1.548.871q-.952.952-.952 2.298t.952 2.298T5 21.75t2.298-.952t.952-2.298q0-2.85-2.5-3.201V14q0-.75.75-.75h4.75v2.049q-2.5.351-2.5 3.201q0 1.346.952 2.298T12 21.75t2.298-.952t.952-2.298q0-2.85-2.5-3.201V13.25h4.75q.75 0 .75.75v1.299q-2.5.351-2.5 3.201q0 1.346.952 2.298T19 21.75t2.298-.952t.952-2.298t-.952-2.298q-.675-.675-1.548-.871V14q0-2.25-2.25-2.25h-4.75V8.745q3-.123 3-3.245q0-3.25-3.25-3.25");
}

</style>
