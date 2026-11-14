<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itb3me6ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:safe-space" /></template>
<style>
.itb3me6ek {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v1.826l-2.577-.92Q18.346 12.5 18 12.5t-.673.117l-3.5 1.25q-.144.051-.28.124q-.135.074-.257.167q-.123.093-.229.204t-.196.236q-.088.126-.157.263q-.068.138-.115.285q-.046.146-.069.298t-.024.306V18q0 1.863 1.003 3.25H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568m14.317 4.651l3.5 1.25q.11.039.202.109t.159.165t.102.205t.035.227V18q0 3.207-3.987 4.702q-.127.048-.263.048t-.263-.048Q13.75 21.207 13.75 18v-2.25q0-.116.035-.227q.035-.11.102-.205t.159-.165t.202-.109l3.5-1.25q.122-.044.252-.044t.252.044m-3.002 2.485l2.75-.983l2.75.983V18q0 2.071-2.75 3.195q-2.75-1.124-2.75-3.195zm2.75.345l-1.5.535V18q0 1.074 1.5 1.824q1.5-.75 1.5-1.824v-.841z");
}

</style>
