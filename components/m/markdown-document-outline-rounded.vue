<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt6pqmada"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-document-outline-rounded" /></template>
<style>
.lt6pqmada {
  fill: currentColor;
  d: path("M6.346 20q-.986 0-1.676-.686q-.69-.685-.69-1.699V6.385q0-.981.69-1.683T6.346 4h11.42q.94 0 1.587.715q.647.714.647 1.67V11q0 .213-.144.356t-.357.144t-.356-.144T19 11V6.385q0-.56-.392-.972T17.634 5H6.346q-.58 0-.973.413t-.392.971v11.232q0 .588.392.986q.393.398.973.398h3.846q.213 0 .357.144t.143.357t-.143.356t-.357.143zm1.885-3.75h2.461v-1H8.231q-.213 0-.356.144t-.144.357t.144.356t.356.143m0-3.75h3.813q.487-.477 1.12-.738q.634-.262 1.374-.262H8.231q-.213 0-.356.144t-.144.357t.144.356t.356.143m8.308 2.385H14.5q-.173 0-.298.125t-.125.298V20.5q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356v-5.058q0-.642.466-1.1q.466-.457 1.12-.457h4.758q.654 0 1.116.457q.463.458.463 1.1V20.5q0 .213-.144.356t-.357.144t-.356-.144T20 20.5v-5.192q0-.174-.134-.299q-.135-.125-.308-.125h-2.02v3.75q0 .213-.143.357t-.357.143t-.356-.143t-.143-.357zm-11.558.461V19V5z");
}

</style>
