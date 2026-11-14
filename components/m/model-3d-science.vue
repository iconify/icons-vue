<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4hz0k0zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:model-3d-science" /></template>
<style>
.f4hz0k0zy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.17 2.27q-1.17-.619-2.34 0L4.08 5.844q-.335.178-.586.406q.19-.001.357.087L12 10.651l8.149-4.314q.167-.088.357-.087q-.251-.228-.586-.406zm7.996 5.076q-.108.207-.315.317l-8.101 4.289V21.5q0 .125-.041.243q-.04.119-.117.217q.289-.077.578-.23l6.75-3.574q1.33-.705 1.33-2.21V8.054q0-.379-.084-.708M11.408 21.96q-.077-.098-.117-.217q-.041-.118-.041-.243v-9.548L3.149 7.663q-.207-.11-.315-.317q-.084.328-.084.708v7.892q0 1.505 1.33 2.21l6.75 3.574q.289.153.578.23");
}

</style>
