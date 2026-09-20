<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8nqzxbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-alert-rounded" /></template>
<style>
.u8nqzxbhu {
  fill: currentColor;
  d: path("M19.48 10.52q-.21-.21-.21-.52t.21-.52t.52-.21t.52.21t.21.52t-.21.52t-.52.21t-.52-.21m.163-3.163Q19.5 7.214 19.5 7V4q0-.213.143-.357T20 3.5t.357.143T20.5 4v3q0 .214-.143.357T20 7.5t-.357-.143m-12.766 3.15Q6 9.632 6 8.386t.877-2.123Q7.754 5.385 9 5.385t2.123.877T12 8.385t-.877 2.123T9 11.385t-2.123-.877M2 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838q1.416-.679 2.834-1.018q1.417-.34 2.836-.34t2.837.34t2.832 1.018q.61.298.97.838q.361.539.361 1.158v.608q0 .44-.299.74q-.299.298-.74.298H3.04q-.441 0-.74-.299t-.3-.739");
}

</style>
