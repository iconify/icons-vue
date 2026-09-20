<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt8uxpbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-4-outline-sharp" /></template>
<style>
.dt8uxpbjt {
  fill: currentColor;
  d: path("M9.877 11.503Q9 10.622 9 9.385v-2.75q0-.473.325-.804q.326-.331.79-.331q.299 0 .54.137q.241.136.403.365q.161-.229.403-.365q.241-.137.539-.137t.54.137t.402.365q.162-.229.403-.365q.242-.137.53-.137q.48 0 .803.331q.322.33.322.803v2.75q0 1.238-.877 2.12q-.877.88-2.123.88t-2.123-.88m3.535-.707Q14 10.209 14 9.384v-2.5h-4v2.5q0 .825.588 1.413t1.412.587t1.413-.587M5 19.616v-1.647q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v1.646zm1-1h12v-.647q0-.332-.215-.625q-.214-.292-.593-.494q-1.234-.598-2.546-.916T12 15.616t-2.646.318t-2.546.916q-.38.202-.593.494Q6 17.637 6 17.97zm6-11.731");
}

</style>
