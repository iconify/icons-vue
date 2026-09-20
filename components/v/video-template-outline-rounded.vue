<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz8qqmbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-template-outline-rounded" /></template>
<style>
.vz8qqmbxt {
  fill: currentColor;
  d: path("M5.558 22q-.69 0-1.153-.462t-.463-1.153v-.75h1v.75q0 .269.173.442t.443.173h12.884q.27 0 .443-.173t.173-.442v-.75h1v.75q0 .69-.463 1.153T18.442 22zm-.942-4.75q-.691 0-1.153-.462T3 15.635v-7.27q0-.69.463-1.152t1.152-.463h14.77q.69 0 1.152.463T21 8.366v7.269q0 .69-.463 1.153t-1.152.462zM3.942 4.365v-.75q0-.69.463-1.153T5.558 2h12.884q.69 0 1.153.463t.463 1.152v.75h-1v-.75q0-.269-.174-.442Q18.712 3 18.443 3H5.558q-.27 0-.442.173q-.174.173-.174.443v.75zm.673 11.885h14.77q.269 0 .442-.173t.173-.442v-7.27q0-.269-.173-.442t-.442-.173H4.615q-.269 0-.442.173T4 8.366v7.269q0 .269.173.442t.443.173m5.711-1.634L14.673 12l-4.346-2.615z");
}

</style>
