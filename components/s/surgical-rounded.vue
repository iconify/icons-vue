<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7hzekb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:surgical-rounded" /></template>
<style>
.u7hzekb9n {
  fill: currentColor;
  d: path("M21.635 19.212h-8.481q-.25 0-.375-.159t-.125-.341t.128-.342t.378-.158h8.475q.213 0 .356.143t.144.356t-.144.357t-.356.144M9.692 17.858q-.665.684-1.554 1.028t-1.828.345h-.6q-.333 0-.673-.056t-.645-.18q-.275-.08-.422-.304t-.147-.505q0-.198.071-.38q.071-.183.214-.325L7.694 13.9q.243-.242.566-.242t.565.242l1.323 1.323q.216.216.348.483q.133.267.133.575t-.123.587t-.339.496zm2.524-3.843q-.243.243-.566.243t-.565-.242l-1.196-1.197q-.243-.242-.243-.565t.243-.565l6.384-6.385q.148-.148.31-.213q.163-.064.342-.064t.339.064q.159.065.307.213L18.6 6.333q.148.148.213.31t.064.342t-.064.338t-.213.308z");
}

</style>
