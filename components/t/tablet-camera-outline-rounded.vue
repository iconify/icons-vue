<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfgy76bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tablet-camera-outline-rounded" /></template>
<style>
.hfgy76bhv {
  fill: currentColor;
  d: path("M18.5 19V6h-13v13H3.616q-.672 0-1.144-.472T2 17.385V6.615q0-.67.472-1.143Q2.944 5 3.616 5h16.769q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472zM4.5 6h-.885q-.269 0-.442.173T3 6.616v10.769q0 .269.173.442t.443.173H4.5zm15 0v12h.885q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T20.385 6zm0 0H21zm-15 0H3zm4.942 15q-.528 0-.908-.38t-.38-.909v-3.403q0-.53.38-.909q.38-.38.908-.38h.847l.865-.865h1.692l.866.865h.846q.529 0 .908.38q.38.38.38.909v3.403q0 .53-.38.91q-.38.379-.908.379zm3.613-1.945Q13.5 18.61 13.5 18t-.445-1.045T12 16.519t-1.055.436T10.5 18t.445 1.055T12 19.5t1.055-.445");
}

</style>
