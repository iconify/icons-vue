<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc9p-sbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-10-select-outline-rounded" /></template>
<style>
.hc9p-sbtc {
  fill: currentColor;
  d: path("M9.539 16.885h3.538q.27 0 .442-.174t.173-.442V7.731q0-.27-.173-.442t-.442-.173H9.539q-.27 0-.443.173t-.173.442v8.538q0 .27.173.443t.443.173m0 1.23q-.789 0-1.318-.528q-.529-.53-.529-1.318V7.731q0-.789.53-1.317q.528-.53 1.317-.53h3.538q.789 0 1.317.53q.529.528.529 1.317v8.538q0 .789-.529 1.318q-.528.529-1.317.529zm-5.847-11H2.308q-.26 0-.438-.177q-.178-.178-.178-.438t.178-.437t.438-.178h1.404q.51 0 .86.35q.351.352.351.861V17.5q0 .26-.178.438t-.437.178t-.438-.178t-.178-.438zm17.766 11h-3.65q-.214 0-.357-.143t-.143-.357t.143-.356t.357-.144h3.5v-2h-3.15q-.364 0-.607-.243t-.243-.606v-2.3q0-.364.243-.607t.607-.243h3.65q.213 0 .356.143t.144.357t-.144.356t-.356.144h-3.5v2h3.15q.363 0 .606.243t.244.607v2.3q0 .363-.244.606q-.243.244-.606.244");
}

</style>
