<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkmmj_bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shopping-bag-rounded" /></template>
<style>
.xkmmj_bra {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V8.615q0-.69.463-1.152T6.616 7H8.5v-.5q0-1.458 1.021-2.479T12 3t2.479 1.021T15.5 6.5V7h1.885q.69 0 1.152.463T19 8.616v10.769q0 .69-.463 1.153T17.385 21zM9.5 7h5v-.5q0-1.056-.722-1.778T12 4t-1.778.722T9.5 6.5zm5.857 3.857q.143-.143.143-.357V8h-1v2.5q0 .214.143.357T15 11t.357-.143m-6 0q.143-.143.143-.357V8h-1v2.5q0 .214.143.357T9 11t.357-.143");
}

</style>
