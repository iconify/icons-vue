<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3lhiifke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:multicooker-sharp" /></template>
<style>
.e3lhiifke {
  fill: currentColor;
  d: path("M8.5 5.5v-.885q0-.67.472-1.143Q9.444 3 10.116 3h3.769q.67 0 1.143.472q.472.472.472 1.144V5.5h2.885q.67 0 1.143.472q.472.472.472 1.144V9H4V7.116q0-.672.472-1.144T5.616 5.5zM5.616 20q-.672 0-1.144-.472T4 18.385V10h3.5v1.5q0 .671.472 1.143t1.143.472h5.77q.67 0 1.143-.472q.472-.472.472-1.143V10H20v8.385q0 .67-.472 1.143q-.472.472-1.143.472zm2.924-2.845q.23-.23.23-.54t-.23-.539t-.54-.23t-.54.23t-.23.54t.23.539t.54.23t.54-.23m4 0q.23-.23.23-.54t-.23-.539t-.54-.23t-.54.23t-.23.54t.23.539t.54.23t.54-.23m4 0q.23-.23.23-.54t-.23-.539t-.54-.23t-.54.23t-.23.54t.23.539t.54.23t.54-.23m-7.424-5.04q-.27 0-.443-.173T8.5 11.5V10h7v1.5q0 .27-.173.442q-.173.173-.442.173zM9.5 5.5h5v-.885q0-.269-.173-.442T13.885 4h-3.77q-.269 0-.442.173t-.173.443z");
}

</style>
