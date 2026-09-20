<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf6c4kb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-add-rounded" /></template>
<style>
.yf6c4kb2p {
  fill: currentColor;
  d: path("M18.25 10.5h-2.5q-.213 0-.357-.143T15.25 10t.143-.357t.357-.143h2.5V7q0-.213.143-.357t.357-.143t.357.143t.143.357v2.5h2.5q.214 0 .357.143t.143.357t-.143.357t-.357.143h-2.5V13q0 .214-.143.357t-.357.143t-.357-.143T18.25 13zm-11.373.008Q6 9.63 6 8.385t.877-2.123T9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H3.04q-.441 0-.74-.299t-.3-.739");
}

</style>
