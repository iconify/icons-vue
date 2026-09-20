<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoia8i66e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:newsstand-rounded" /></template>
<style>
.zoia8i66e {
  fill: currentColor;
  d: path("M3 19.385q-.213 0-.356-.144q-.144-.144-.144-.357t.144-.356t.356-.144h18q.213 0 .356.144t.144.357t-.144.356t-.356.144zm1.99-3.913q-.144-.144-.144-.356v-6q0-.213.144-.357q.144-.143.357-.143t.356.143t.143.357v6q0 .212-.144.356t-.357.144t-.356-.144m3.77 0q-.144-.144-.144-.356v-10q0-.213.144-.357q.144-.143.357-.143t.356.143t.144.357v10q0 .212-.145.356t-.356.144t-.356-.144m3.769 0q-.144-.144-.144-.356v-10q0-.213.144-.357t.357-.143t.356.143t.143.357v10q0 .212-.143.356q-.144.144-.357.144t-.356-.144m6.595-.102q-.175.1-.379.043q-.203-.056-.302-.23l-3-5.25q-.104-.177-.047-.382t.231-.305t.38-.044t.302.23l3 5.25q.103.178.047.383t-.232.305");
}

</style>
