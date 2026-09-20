<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn5u0mb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pixel-9-pro-fold" /></template>
<style>
.wn5u0mb5g {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20zM12 19h7.385q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T19.385 5H12zm-6.5-7.5h4q.214 0 .357-.143T10 11t-.143-.357T9.5 10.5h-4q-.213 0-.357.143T5 11t.143.357t.357.143M16 7.77q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23M5.5 7.5h4q.214 0 .357-.143T10 7t-.143-.357T9.5 6.5h-4q-.213 0-.357.143T5 7t.143.357t.357.143");
}

</style>
