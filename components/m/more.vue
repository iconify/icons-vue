<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjm3ud-1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:more" /></template>
<style>
.pjm3ud-1q {
  fill: currentColor;
  d: path("M9.173 19q-.379 0-.727-.164q-.348-.165-.565-.463L3 12l4.88-6.373q.218-.298.566-.462T9.173 5h10.212q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472zm1.251-6.46q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.539-.23m3.5 0q.23-.23.23-.54t-.23-.54t-.54-.23q-.309 0-.539.23t-.23.54t.23.54t.54.23t.539-.23m3.5 0q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.539-.23");
}

</style>
