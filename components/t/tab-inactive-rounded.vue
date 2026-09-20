<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te6dccb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-inactive-rounded" /></template>
<style>
.te6dccb5v {
  fill: currentColor;
  d: path("M8.385 21q-.69 0-1.153-.462t-.463-1.153V17.23H4.616q-.691 0-1.153-.463T3 15.616v-1.193q0-.213.143-.357t.357-.143t.357.143t.143.357v1.193q0 .269.173.442t.443.173h2.153V8.384q0-.69.463-1.152t1.152-.463h7.847V4.616q0-.27-.173-.443T15.616 4h-1.193q-.213 0-.357-.143t-.143-.357t.143-.357t.357-.143h1.193q.69 0 1.152.463t.463 1.152V6.77h2.153q.691 0 1.153.463T21 8.384v11q0 .691-.463 1.153T19.385 21zM3.5 11.558q-.213 0-.357-.143T3 11.058V9.192q0-.213.143-.357t.357-.143t.357.143t.143.357v1.866q0 .213-.143.357t-.357.143m0-5.231q-.213 0-.357-.143T3 5.827V4.616q0-.691.463-1.153T4.615 3h1.212q.214 0 .357.143t.143.357t-.143.357T5.827 4H4.616q-.27 0-.443.173T4 4.616v1.211q0 .214-.143.357t-.357.143M9.192 4q-.213 0-.357-.143T8.692 3.5t.143-.357T9.192 3h1.866q.213 0 .357.143t.143.357t-.143.357t-.357.143z");
}

</style>
