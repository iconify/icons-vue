<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrtit1t8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticky-note-2-outline-rounded" /></template>
<style>
.wrtit1t8z {
  fill: currentColor;
  d: path("M5.616 19H14v-4.192q0-.349.23-.578t.578-.23H19V5.616q0-.27-.173-.443T18.385 5H5.615q-.269 0-.442.173T5 5.616v12.769q0 .269.173.442t.443.173m0 1q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h12.769q.67 0 1.143.472q.472.472.472 1.144v8.001q0 .323-.13.628t-.349.522l-4.754 4.754q-.217.218-.522.348t-.628.131zm5.884-6.538H8.385q-.214 0-.357-.144q-.144-.143-.144-.356t.144-.357t.357-.143H11.5q.214 0 .357.143t.143.357t-.143.356t-.357.144M15.616 9.5H8.385q-.214 0-.357-.143q-.144-.143-.144-.357t.144-.357t.357-.143h7.23q.214 0 .357.143q.144.143.144.357t-.144.357t-.356.143M5 19V5z");
}

</style>
