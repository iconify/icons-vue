<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xhpul-buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-28-regular" /></template>
<style>
.xhpul-buw {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zM6.75 4.5A2.25 2.25 0 0 0 4.5 6.75v14.5a2.25 2.25 0 0 0 2.25 2.25h14.5a2.25 2.25 0 0 0 2.25-2.25V6.75a2.25 2.25 0 0 0-2.25-2.25zm14.5 15.501a.75.75 0 0 1 0 1.5H6.75a.75.75 0 0 1 0-1.5zm0-4.003a.75.75 0 0 1 0 1.5H6.75a.75.75 0 1 1 0-1.5zM11.502 6a.75.75 0 0 1 .69.458l2.748 6.503a.75.75 0 1 1-1.38.584l-.442-1.043H9.882l-.442 1.043a.75.75 0 1 1-1.38-.585l2.75-6.503A.75.75 0 0 1 11.503 6m6.248 0a.75.75 0 0 1 .75.75V8h1.25a.75.75 0 0 1 0 1.5H18.5v1.248a.75.75 0 0 1-1.5 0V9.5h-1.248a.75.75 0 0 1 0-1.5H17V6.75a.75.75 0 0 1 .75-.75m-7.233 5.002h1.967l-.983-2.327z");
}

</style>
