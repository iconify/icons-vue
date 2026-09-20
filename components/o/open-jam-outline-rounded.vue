<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqn2wubki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-jam-outline-rounded" /></template>
<style>
.tqn2wubki {
  fill: currentColor;
  d: path("M11.5 18.77h-4q-.213 0-.357.143T7 19.269t.143.357t.357.143h9q.214 0 .357-.143t.143-.357t-.143-.356t-.357-.144h-4v-8.546l1.746 1.746q.14.14.344.15t.364-.15t.16-.353q0-.195-.16-.354l-2.388-2.389q-.243-.242-.566-.242t-.565.242l-2.389 2.389q-.14.14-.15.344t.15.363t.354.16t.354-.16l1.746-1.746zM4.616 15q-.691 0-1.153-.462T3 13.385v-7.77q0-.69.463-1.152T4.615 4h14.77q.69 0 1.152.463T21 5.616v7.769q0 .69-.463 1.153T19.385 15H15.5q-.213 0-.357-.143T15 14.5t.143-.357T15.5 14h3.885q.23 0 .423-.192t.192-.423v-7.77q0-.23-.192-.423T19.385 5H4.615q-.23 0-.423.192T4 5.616v7.769q0 .23.192.423t.423.192H8.5q.214 0 .357.143T9 14.5t-.143.357T8.5 15z");
}

</style>
