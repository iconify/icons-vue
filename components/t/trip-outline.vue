<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfj05q4rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trip-outline" /></template>
<style>
.zfj05q4rj {
  fill: currentColor;
  d: path("M4.616 20q-.672 0-1.144-.472T3 18.385v-9.77q0-.67.472-1.143Q3.944 7 4.616 7H9V5.615q0-.67.472-1.143Q9.944 4 10.616 4h2.769q.67 0 1.143.472q.472.472.472 1.143V7h4.385q.67 0 1.143.472q.472.472.472 1.144v9.769q0 .67-.472 1.143q-.472.472-1.143.472zM10 7h4V5.615q0-.23-.192-.423T13.385 5h-2.77q-.23 0-.423.192T10 5.615zM7 8H4.616q-.231 0-.424.192T4 8.616v9.769q0 .23.192.423t.423.192H7zm9 11V8H8v11zm1-11v11h2.385q.23 0 .423-.192t.192-.424V8.616q0-.231-.192-.424T19.385 8zm-5 5.5");
}

</style>
