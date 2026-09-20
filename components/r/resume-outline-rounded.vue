<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4a3o4b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:resume-outline-rounded" /></template>
<style>
.g4a3o4b8c {
  fill: currentColor;
  d: path("M7.23 16.116V7.885q0-.214.144-.357q.143-.144.357-.144t.357.144t.143.356v8.231q0 .214-.143.357q-.144.143-.357.143t-.357-.143q-.143-.143-.143-.357m4.602-.227l5.338-3.192q.212-.13.305-.308t.093-.388t-.093-.389t-.305-.307L11.833 8.11q-.106-.055-.205-.08q-.1-.025-.205-.025q-.323 0-.565.22t-.243.587v6.373q0 .368.243.588t.565.22q.106 0 .205-.025t.205-.08m-.217-1.087V9.198L16.298 12zm0-2.802");
}

</style>
