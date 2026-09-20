<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb9ejgkgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:other-houses-rounded" /></template>
<style>
.yb9ejgkgf {
  fill: currentColor;
  d: path("M5 18.385v-7.53l-1.538 1.199q-.178.135-.366.104t-.323-.208t-.11-.365q.023-.189.195-.324l8.148-6.259q.217-.162.472-.243T12 4.68t.513.08t.462.243l8.173 6.26q.171.134.193.322q.02.189-.114.366q-.135.171-.323.202q-.188.03-.36-.104L19 10.856v7.529q0 .67-.472 1.143q-.472.472-1.143.472H6.615q-.67 0-1.143-.472Q5 19.056 5 18.385m3-3.616q.31 0 .54-.23T8.77 14t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m4 0q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m4 0q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23");
}

</style>
