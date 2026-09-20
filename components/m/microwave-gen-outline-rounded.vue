<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chsbphbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:microwave-gen-outline-rounded" /></template>
<style>
.chsbphbnq {
  fill: currentColor;
  d: path("M4.616 19q-.672 0-1.144-.472T3 17.385V6.615q0-.67.472-1.143Q3.944 5 4.616 5h14.769q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472zm0-1h14.769q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T19.385 6H4.615q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173m2.076-1.884h6.616q.348 0 .578-.23t.23-.578V8.692q0-.348-.23-.578t-.578-.23H6.692q-.348 0-.577.23q-.23.23-.23.578v6.616q0 .348.23.578t.577.23m11.463-.23q.23-.23.23-.54t-.23-.54t-.54-.229t-.539.23t-.23.54q0 .309.23.539t.54.23t.539-.23m-11.27-.77V8.885h6.23v6.23zm11.27-2.576q.23-.23.23-.54t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23t.539-.23m0-3.347q.23-.23.23-.54q0-.309-.23-.538t-.54-.23t-.539.23t-.23.539t.23.54t.54.229q.309 0 .539-.23M4 18V6z");
}

</style>
