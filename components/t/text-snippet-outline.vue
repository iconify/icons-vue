<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl20xhbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-snippet-outline" /></template>
<style>
.vl20xhbzs {
  fill: currentColor;
  d: path("M5.616 19h12.769q.269 0 .442-.173t.173-.442V9.614L14.387 5H5.616q-.27 0-.443.173T5 5.616v12.769q0 .269.173.442t.443.173m0 1q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h9.173L20 9.211v9.173q0 .672-.472 1.144T18.385 20zM7.5 16h9v-1h-9zm0-3.5h9v-1h-9zm0-3.5h5.73V8H7.5zM5 19V5z");
}

</style>
