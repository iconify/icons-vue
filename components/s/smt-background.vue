<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path clip-rule="evenodd" class="zcscuv3oy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:smt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.zcscuv3oy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m12.058 4.889l-5.73 4.404L4 16.386l5.747-3.955l2.293 6.68l2.271-6.68L20 16.386l-2.2-7.093zm-.41 1.026L6.791 9.666l-1.698 5.285l4.506-3.138zm.778 0l4.862 3.751h-.004l1.698 5.285l-4.507-3.138zm-.351.751l-1.867 4.89h3.587zm0 10.667l-1.867-4.889h3.587z");
}

</style>
