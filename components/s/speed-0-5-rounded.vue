<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj6t9498w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-0-5-rounded" /></template>
<style>
.qj6t9498w {
  fill: currentColor;
  d: path("M10.75 16.5q-.213 0-.357-.143T10.25 16t.143-.357t.357-.143h2.885q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.442-.173h-2.577q-.348 0-.578-.23t-.23-.578V8.308q0-.348.23-.578t.578-.23h3.692q.214 0 .357.143T15.25 8t-.143.357t-.357.143h-3.5v3h2.385q.69 0 1.152.463t.463 1.153v1.769q0 .69-.462 1.153t-1.153.462zm-2.857-.143Q7.75 16.214 7.75 16t.143-.357t.357-.143t.357.143t.143.357t-.143.357t-.357.143t-.357-.143");
}

</style>
