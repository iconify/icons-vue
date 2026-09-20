<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zijl-0kkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-off-20-filled" /></template>
<style>
.zijl-0kkc {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-1.856-1.855a8 8 0 0 1-11.29-11.29L2.146 2.854a.5.5 0 0 1 0-.708M7.5 10A1.5 1.5 0 0 0 6 11.5c0 1.116.459 2.01 1.212 2.615C7.953 14.71 8.947 15 10 15s2.047-.29 2.788-.885q.172-.139.322-.298L9.293 10zM10 2a8 8 0 0 1 6.616 12.495l-2.635-2.635q.018-.176.019-.36a1.5 1.5 0 0 0-1.5-1.5h-.379l-1.218-1.218A1.998 1.998 0 0 0 10 5c-.779 0-1.453.446-1.783 1.096L5.504 3.383A7.96 7.96 0 0 1 10 2");
}

</style>
