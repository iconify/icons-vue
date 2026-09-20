<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxs2dnbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-add-outline-rounded" /></template>
<style>
.mxs2dnbme {
  fill: currentColor;
  d: path("M11.5 14.5V17q0 .214.143.357T12 17.5t.357-.143T12.5 17v-2.5H15q.214 0 .357-.143T15.5 14t-.143-.357T15 13.5h-2.5V11q0-.213-.143-.357T12 10.5t-.357.143T11.5 11v2.5H9q-.213 0-.357.143T8.5 14t.143.357T9 14.5zM6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h7.213q.323 0 .628.13t.522.349L18.52 7.02q.217.218.348.522t.131.628v11.214q0 .69-.463 1.153T17.385 21zM14 7.192V4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192h10.77q.23 0 .423-.192t.192-.424V8h-3.192q-.349 0-.578-.23T14 7.192M6 4v4zv16z");
}

</style>
