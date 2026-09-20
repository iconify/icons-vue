<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a25bk1bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-4-outline-rounded" /></template>
<style>
.a25bk1bjk {
  fill: currentColor;
  d: path("M9.877 11.508Q9 10.63 9 9.385v-2.75q0-.471.322-.803t.794-.332q.298 0 .539.137q.241.136.403.365q.161-.229.403-.365q.241-.137.539-.137t.54.137t.402.365q.162-.229.403-.365q.241-.137.54-.137q.47 0 .793.332q.322.332.322.803v2.75q0 1.246-.877 2.123T12 12.385t-2.123-.877m3.535-.711Q14 10.21 14 9.385v-2.5h-4v2.5q0 .824.588 1.412t1.412.587t1.413-.587M5 18.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H6.04q-.441 0-.74-.299t-.3-.739m1 .039h12v-.647q0-.332-.215-.625q-.214-.292-.593-.494q-1.234-.598-2.542-.916T12 15.616t-2.65.318t-2.542.916q-.38.202-.593.494Q6 17.637 6 17.97zm6-11.731");
}

</style>
