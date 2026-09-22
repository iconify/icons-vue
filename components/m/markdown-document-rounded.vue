<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdn6dpbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markdown-document-rounded" /></template>
<style>
.rdn6dpbcs {
  fill: currentColor;
  d: path("M16.539 14.885H14.5q-.173 0-.298.125t-.125.298V20.5q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356v-5.058q0-.642.466-1.1q.466-.457 1.12-.457h4.758q.654 0 1.116.457q.463.458.463 1.1V20.5q0 .213-.144.356t-.357.144t-.356-.144T20 20.5v-5.192q0-.174-.134-.299q-.135-.125-.308-.125h-2.02v3.75q0 .213-.143.357t-.357.143t-.356-.143t-.143-.357zM8.23 16.25h2.461v2.942q0 .344-.232.576T9.885 20H6.346q-.986 0-1.676-.686q-.69-.685-.69-1.699V6.385q0-.981.69-1.683T6.346 4h11.42q.94 0 1.587.715q.647.714.647 1.67v4.307q0 .344-.232.576t-.576.232H8.231q-.213 0-.356.144t-.144.357t.144.356t.356.143h3.813q-.621.489-.967 1.2q-.346.712-.385 1.55H8.231q-.213 0-.356.144t-.144.357t.144.356t.356.143");
}

</style>
