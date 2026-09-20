<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alcukek_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:oil-barrel-outline-rounded" /></template>
<style>
.alcukek_x {
  fill: currentColor;
  d: path("M4.48 20q-.212 0-.356-.144t-.143-.357t.143-.356t.357-.143h1.211v-6.5H4.481q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h1.211V5H4.481q-.213 0-.356-.144t-.144-.357t.144-.356T4.48 4H19.5q.213 0 .356.144t.144.357t-.144.356T19.5 5h-1.192v6.5H19.5q.213 0 .356.144t.144.357t-.144.356t-.356.143h-1.192V19H19.5q.213 0 .356.144t.144.357t-.144.356T19.5 20zm2.212-1h10.616v-6.5h-.5q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h.5V5H6.692v6.5h.5q.213 0 .357.144t.143.357t-.143.356t-.357.143h-.5zm7.077-4.351q.731-.716.731-1.733q0-.404-.093-.716t-.386-.69l-1.398-1.665q-.25-.295-.625-.295q-.376 0-.62.292l-1.4 1.662q-.291.379-.385.682t-.093.72q0 1.023.729 1.741q.728.719 1.769.719t1.771-.717M6.692 19V5z");
}

</style>
