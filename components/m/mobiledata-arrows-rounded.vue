<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5_-x7b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobiledata-arrows-rounded" /></template>
<style>
.k5_-x7b6i {
  fill: currentColor;
  d: path("M8.5 18.073V9.591q0-.214.143-.357T9 9.09t.357.143t.143.357v8.482l1.735-1.734q.146-.147.344-.153t.363.153q.166.165.169.356q.003.192-.163.357l-2.382 2.383q-.243.242-.566.242t-.565-.242l-2.383-2.383q-.146-.146-.153-.347t.159-.366q.165-.16.354-.163t.354.163zm6-12.157L12.754 7.66q-.14.141-.344.15t-.364-.15t-.16-.353t.16-.354l2.388-2.388q.243-.243.566-.243t.566.243l2.388 2.388q.14.14.15.344t-.15.364t-.354.16t-.354-.16L15.5 5.916v7.059q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357z");
}

</style>
