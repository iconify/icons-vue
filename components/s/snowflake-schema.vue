<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_zke3l3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:snowflake-schema" /></template>
<style>
.q_zke3l3j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 5.75q0-2-2-2t-2 2v.5q0 1.581 1.25 1.912v1.119Q3.5 9.516 3.5 11.5v1q0 .932.659 1.591q.475.475 1.091.607v1.14Q4 16.169 4 17.75v.5q0 2 2 2t2-2v-.5q0-1.581-1.25-1.912v-1.14q.616-.132 1.091-.607q.569-.569.647-1.341H9q0 1.036.732 1.768t1.768.732h1q1.036 0 1.768-.732T15 12.75h.512q.078.772.647 1.341q.475.475 1.091.607v1.14Q16 16.169 16 17.75v.5q0 2 2 2t2-2v-.5q0-1.581-1.25-1.912v-1.14q.616-.132 1.091-.607q.659-.659.659-1.591v-1q0-1.984-1.75-2.219V8.162Q20 7.831 20 6.25v-.5q0-2-2-2t-2 2v.5q0 1.581 1.25 1.912v1.119q-1.637.219-1.743 1.969H15q0-1.036-.732-1.768T12.5 8.75h-1q-2.5 0-2.5 2.5h-.512q-.078-.772-.647-1.341q-.475-.475-1.091-.607v-1.14Q8 7.831 8 6.25z");
}

</style>
