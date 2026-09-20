<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3lfqgbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-score-rounded" /></template>
<style>
.k3lfqgbcn {
  fill: currentColor;
  d: path("M8.808 6.077h1.846V4.231H8.808zm3.692 0V4.231h1.846v1.846zm-3.692 7.385v-1.846h1.846v1.846zm7.384-3.693V7.923h1.847v1.846zm0 3.693v-1.846h1.847v1.846zm-3.692 0v-1.846h1.846v1.846zm3.692-7.385V4.231h1.847v1.846zm-5.538 1.846V6.077H12.5v1.846zm-4.55 11.395q-.142-.144-.142-.356V4.73q0-.213.144-.356t.356-.144t.356.144t.144.356v1.346h1.846v1.846H6.962v1.846h1.846v1.847H6.962v7.346q0 .212-.144.356q-.144.143-.357.143t-.356-.143m8.241-7.703V9.77h1.846v1.847zm-3.692 0V9.77H12.5v1.847zM8.808 9.77V7.923h1.846v1.846zm3.692 0V7.923h1.846v1.846zm1.846-1.846V6.077h1.846v1.846z");
}

</style>
