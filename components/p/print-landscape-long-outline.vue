<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahdzcrbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-long-outline" /></template>
<style>
.ahdzcrbqx {
  fill: currentColor;
  d: path("M5 12.866h1v3.5q0 .269.173.451q.173.183.443.183h11.769q.269 0 .442-.173t.173-.442V7.539h1v8.846q0 .67-.472 1.143q-.472.472-1.143.472H6.615q-.67 0-1.143-.472Q5 17.056 5 16.385zM14.23 5h1.924v.923h2.23q.678 0 1.147.457T20 7.539q0 .167-.089.465q-.088.298-.23.652t-.306.753l-.325.787q-.206.468-.432 1.007q-.226.54-.512 1.168q-.198.454-.602.724t-.883.27H4.846q-.856 0-1.302-.7t-.1-1.46q.458-1.118.835-2.251t.577-1.858q.13-.54.584-.856q.454-.317 1.02-.317h1.31V5h1.922v.923h4.539zm2.897 7q.46-.927.982-2.075t.853-2.136q.115-.327-.096-.597t-.539-.269H6.44q-.192 0-.346.116q-.154.115-.192.307q-.275 1.021-.71 2.153q-.436 1.132-.827 2.059q-.154.327.01.567t.49.24h11.666q.192 0 .346-.105q.154-.106.25-.26m1.97-5.077H6.44zM19 17H6z");
}

</style>
