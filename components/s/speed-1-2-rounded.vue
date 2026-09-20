<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0bvvicjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-1-2-rounded" /></template>
<style>
.j0bvvicjf {
  fill: currentColor;
  d: path("M7.874 16.357q-.143-.143-.143-.357V9.116q0-.27-.173-.443q-.174-.173-.443-.173h-.884q-.214 0-.357-.143T5.731 8t.143-.357t.357-.143h.885q.67 0 1.143.472q.472.472.472 1.143V16q0 .214-.143.357t-.357.143t-.357-.143m7.01.143q-.67 0-1.143-.472q-.472-.472-.472-1.144v-1.769q0-.69.463-1.153t1.153-.462h1.769q.269 0 .442-.173t.173-.443V9.115q0-.269-.173-.442t-.442-.173h-2.885q-.213 0-.357-.143T13.27 8t.143-.357t.357-.143h2.885q.69 0 1.153.463t.462 1.153v1.769q0 .69-.462 1.153t-1.153.462h-1.77q-.269 0-.442.173t-.173.443v1.769q0 .269.173.442t.442.173h2.885q.214 0 .357.143t.143.357t-.143.357t-.357.143zm-4.24-.143Q10.5 16.214 10.5 16t.143-.357T11 15.5t.357.143t.143.357t-.143.357T11 16.5t-.357-.143");
}

</style>
