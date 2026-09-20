<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5v5pb84g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-4-rounded" /></template>
<style>
.u5v5pb84g {
  fill: currentColor;
  d: path("M9.877 11.508Q9 10.63 9 9.385v-2.75q0-.471.322-.803t.794-.332q.298 0 .539.137q.241.136.403.365q.161-.229.403-.365q.241-.137.539-.137t.54.137t.402.365q.162-.229.403-.365q.241-.137.54-.137q.47 0 .793.332q.322.332.322.803v2.75q0 1.246-.877 2.123T12 12.385t-2.123-.877M5 18.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H6.04q-.441 0-.74-.299t-.3-.739");
}

</style>
