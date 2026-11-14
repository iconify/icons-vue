<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi-pvoi3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wave-packet" /></template>
<style>
.oi-pvoi3n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 10.5q-1.312 0-2.442 2.712q-.058.138-.058.288q0 .031.003.062q.008.103.044.199t.097.18t.141.148t.177.103q.138.058.288.058h2.896q1.033 4.5 2.604 4.5t2.604-4.5h2.792q1.033 4.5 2.604 4.5t2.604-4.5h2.909q.143-.003.275-.058q.138-.057.243-.163q.106-.105.163-.243q.056-.138.056-.286v-.002q0-.149-.058-.286Q21.063 10.5 19.75 10.5q-1.196 0-2.24 2.25h-2.851Q13.654 5.25 12 5.25t-2.659 7.5H6.49Q5.446 10.5 4.25 10.5m2.679 3.75q.674 3 1.071 3t1.071-3zm-2.093-1.5Q4.452 12 4.25 12t-.586.75zm6.015 0h2.298q-.774-6-1.149-6t-1.149 6m4.078 1.5q.674 3 1.071 3t1.071-3zm4.235-1.5q.384-.75.586-.75t.586.75z");
}

</style>
