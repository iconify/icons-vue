<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ixdplwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-long-outline-rounded" /></template>
<style>
.t5ixdplwh {
  fill: currentColor;
  d: path("M5 12.866h1v3.5q0 .269.173.451q.173.183.443.183h11.769q.269 0 .442-.173t.173-.442V7.539h1v8.846q0 .67-.472 1.143q-.472.472-1.143.472H6.615q-.67 0-1.143-.472Q5 17.056 5 16.385zm-1.556-1.66q.458-1.12.835-2.252q.377-1.133.577-1.858q.13-.54.585-.857q.453-.316 1.019-.316h1.31v-.115q0-.348.229-.578T8.577 5h.308q.348 0 .577.23t.23.578v.115h4.539v-.115q0-.348.23-.578t.577-.23h.308q.348 0 .578.23t.23.578v.115h2.23q.677 0 1.147.457T20 7.539q0 .167-.089.465q-.088.298-.23.652t-.306.753l-.325.787q-.206.468-.432 1.007q-.226.54-.512 1.168q-.198.454-.602.724t-.883.27H4.846q-.856 0-1.302-.7t-.1-1.46M17.127 12q.46-.927.982-2.075t.853-2.136q.115-.327-.096-.597t-.539-.269H6.44q-.192 0-.346.116q-.154.115-.192.307q-.275 1.021-.71 2.153q-.436 1.132-.827 2.059q-.154.327.01.567t.49.24h11.666q.192 0 .346-.105q.154-.106.25-.26m1.97-5.077H6.44zM19 17H6z");
}

</style>
