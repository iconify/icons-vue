<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7cdjlg5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:platform-canopy" /></template>
<style>
.l7cdjlg5m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.194 5.525Q12 1.897 5.806 5.525q-.209.056-.356.215q-1.733 1.074-3.466 2.716q-.108.102-.169.238q-.061.137-.065.286t.05.288q.053.14.156.248q.05.053.111.096q.06.043.127.073q.068.03.14.046q.072.017.146.019t.146-.011t.142-.039t.132-.065t.116-.091Q4.133 8.486 5.25 7.691v8.059h-1q-1.036 0-1.768.732T1.75 18.25q0 2.5 2.5 2.5h15.5q1.036 0 1.768-.732t.732-1.768t-.732-1.768t-1.768-.732h-1V7.691q1.117.795 2.234 1.853q.054.051.116.091q.063.039.132.065t.142.039t.146.011t.146-.019t.14-.046t.127-.073q.061-.043.111-.096t.091-.116q.039-.063.065-.132t.039-.142q.013-.072.011-.146t-.019-.146t-.046-.14t-.073-.127q-.043-.061-.096-.111q-1.733-1.642-3.466-2.716q-.147-.159-.356-.215M6.75 15.75V6.742q5.25-2.906 10.5 0v9.008z");
}

</style>
