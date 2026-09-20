<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="kh5hltbln"/><circle class="b3zh2cb4p"/><path class="bn5_n2bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:sun-behind-cloud" /></template>
<style>
.b3zh2cb4p {
  cx: 16px;
  cy: 16px;
  r: 9px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.bn5_n2bzj {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M28 20c-.825 0-1.62.125-2.369.357A6.5 6.5 0 0 0 19.5 16c-3.044 0-5.592 2.096-6.299 4.921A4.46 4.46 0 0 0 10.5 20A4.5 4.5 0 0 0 6 24.5c0 .604.123 1.178.339 1.704A5 5 0 0 0 5 26c-2.762 0-5 2.238-5 5s2.238 5 5 5h23a8 8 0 1 0 0-16");
}

.kh5hltbln {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M14 2s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2zm16 12s2 0 2 2s-2 2-2 2h-2s-2 0-2-2s2-2 2-2zM4 14s2 0 2 2s-2 2-2 2H2s-2 0-2-2s2-2 2-2zm3.872-7.957s1.414 1.414 0 2.828s-2.828 0-2.828 0L3.629 7.458s-1.414-1.414 0-2.829c1.415-1.414 2.829 0 2.829 0zm19.085 2.828s-1.414 1.414-2.828 0s0-2.828 0-2.828l1.414-1.414s1.414-1.414 2.828 0s0 2.828 0 2.828z");
}

</style>
