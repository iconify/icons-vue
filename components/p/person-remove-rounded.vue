<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp9-5onjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-remove-rounded" /></template>
<style>
.qp9-5onjc {
  fill: currentColor;
  d: path("M16.616 9.5h4q.213 0 .356.143q.144.143.144.357t-.144.357t-.357.143h-4q-.213 0-.356-.143T16.116 10t.143-.357t.356-.143m-9.738 1.008Q6 9.63 6 8.385t.877-2.123T9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H3.04q-.441 0-.74-.299t-.3-.739");
}

</style>
