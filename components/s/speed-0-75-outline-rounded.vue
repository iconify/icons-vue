<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e66_b2bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-0-75-outline-rounded" /></template>
<style>
.e66_b2bzl {
  fill: currentColor;
  d: path("M14.5 16.5q-.213 0-.357-.143T14 16t.143-.357t.357-.143h2.885q.269 0 .442-.173t.173-.442v-1.77q0-.269-.173-.442t-.443-.173h-2.576q-.349 0-.578-.23t-.23-.578V8.308q0-.348.23-.578t.578-.23H18.5q.214 0 .357.143T19 8t-.143.357t-.357.143H15v3h2.385q.69 0 1.152.463T19 13.116v1.769q0 .69-.463 1.153t-1.152.462zm-3.23-8H7.807q-.214 0-.357-.143T7.308 8t.143-.357t.357-.143h3.558q.378 0 .66.268t.282.648q0 .25-.07.43l-1.832 7.275q-.056.171-.181.275t-.302.104q-.263 0-.42-.192t-.087-.431zm-5.127 7.857Q6 16.214 6 16t.143-.357t.357-.143t.357.143T7 16t-.143.357t-.357.143t-.357-.143");
}

</style>
