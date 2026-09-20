<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3rtfgbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:play-lesson" /></template>
<style>
.x3rtfgbhs {
  fill: currentColor;
  d: path("M7.5 4v6.192L9.5 9l2 1.192V4zm7.165 16.528Q13.5 19.364 13.5 17.692q0-1.67 1.174-2.835t2.922-1.165q1.594 0 2.75 1.165t1.154 2.835q0 1.672-1.164 2.836q-1.165 1.164-2.836 1.164t-2.835-1.164m1.97-.951l2.73-1.923l-2.73-1.923zM11.5 17.691q0 .884.251 1.724q.251.839.73 1.585H5.616q-.672 0-1.144-.472T4 19.385V4.615q0-.67.472-1.143Q4.944 3 5.616 3h10.769q.67 0 1.143.472q.472.472.472 1.144v7.107q-.096-.006-.203-.008q-.106-.003-.202-.003q-2.54 0-4.317 1.739t-1.778 4.24");
}

</style>
