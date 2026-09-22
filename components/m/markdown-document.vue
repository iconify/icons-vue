<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da4hmdufl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-document" /></template>
<style>
.da4hmdufl {
  fill: currentColor;
  d: path("M13.077 21v-5.555q0-.655.466-1.107q.466-.453 1.12-.453h4.758q.654 0 1.117.457q.462.458.462 1.1V21h-1v-5.692q0-.174-.134-.299q-.135-.125-.308-.125h-2.02v4.25h-1v-4.25H14.5q-.173 0-.298.126t-.125.298V21zm-4.846-4.75h2.461V20H6.346q-.986 0-1.676-.686q-.69-.685-.69-1.699V6.385q0-.981.69-1.683T6.346 4h11.42q.94 0 1.587.715q.647.714.647 1.67V11.5H8.23q-.212 0-.355.144t-.144.357t.144.356t.356.143h3.813q-.621.489-.967 1.2q-.346.712-.385 1.55H8.231q-.213 0-.356.144t-.144.357t.144.356t.356.143");
}

</style>
