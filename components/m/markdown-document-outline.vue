<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfk3z8bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-document-outline" /></template>
<style>
.wfk3z8bvp {
  fill: currentColor;
  d: path("M10.692 19v1H6.346q-.986 0-1.676-.686q-.69-.685-.69-1.699V6.385q0-.981.69-1.683T6.346 4h11.42q.94 0 1.587.715q.647.714.647 1.67V11.5h-1V6.385q0-.56-.392-.972T17.634 5H6.346q-.58 0-.973.413t-.392.971v11.232q0 .588.392.986q.393.398.973.398zm-2.461-2.75h2.461v-1H8.231q-.213 0-.356.144t-.144.357t.144.356t.356.143m0-3.75h3.813q.487-.477 1.12-.738q.634-.262 1.374-.262H8.231q-.213 0-.356.144t-.144.357t.144.356t.356.143m4.846 8.5v-5.555q0-.655.466-1.107q.466-.453 1.12-.453h4.758q.654 0 1.117.457q.462.458.462 1.1V21h-1v-5.692q0-.174-.134-.299q-.135-.125-.308-.125h-2.02v4.25h-1v-4.25H14.5q-.173 0-.298.126t-.125.298V21zm-8.096-5.654V19V5z");
}

</style>
