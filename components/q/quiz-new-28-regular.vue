<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="omfb4kb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-new-28-regular" /></template>
<style>
.omfb4kb3y {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m.75-11A3.75 3.75 0 0 1 25 6.75v7.75a7.5 7.5 0 0 0-1.5-.874V6.75a2.25 2.25 0 0 0-2.25-2.25H6.75A2.25 2.25 0 0 0 4.5 6.75v14.5a2.25 2.25 0 0 0 2.25 2.25h6.876A7.5 7.5 0 0 0 14.5 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zm-.75 13a.5.5 0 0 0-.5.5V20h-3.5a.5.5 0 0 0 0 1H20v3.5a.5.5 0 0 0 1 0V21h3.5a.5.5 0 0 0 0-1H21v-3.5a.5.5 0 0 0-.5-.5m-7.481 4.001Q13 20.248 13 20.5q.002.51.068 1.001H6.75a.75.75 0 0 1 0-1.5zm1.483-4.003c-.347.461-.64.965-.875 1.5H6.75a.75.75 0 1 1 0-1.5zm-3-9.998a.75.75 0 0 1 .69.458l2.748 6.503a.75.75 0 1 1-1.38.584l-.442-1.043H9.882l-.442 1.043a.75.75 0 1 1-1.38-.585l2.75-6.503A.75.75 0 0 1 11.503 6m6.248 0a.75.75 0 0 1 .75.75V8h1.25a.75.75 0 0 1 0 1.5H18.5v1.248a.75.75 0 0 1-1.5 0V9.5h-1.248a.75.75 0 0 1 0-1.5H17V6.75a.75.75 0 0 1 .75-.75m-7.233 5.002h1.967l-.983-2.327z");
}

</style>
