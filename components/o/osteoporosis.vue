<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye0_5ybqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:osteoporosis" /></template>
<style>
.ye0_5ybqw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.185 8.25Q6.832 6.372 4.57 6.16q-1.119-.105-1.914.532q-.906.727-.906 2.058q0 1.39 1.516 2.983q.137.145.249.267q-.112.122-.249.267Q1.75 13.86 1.75 15.25q0 1.331.906 2.058q.795.637 1.914.532q2.262-.212 2.615-2.09h9.63q.353 1.878 2.615 2.09q1.119.105 1.914-.532q.906-.727.906-2.058q0-1.39-1.516-2.983q-.137-.145-.249-.267q.112-.122.249-.267Q22.25 10.14 22.25 8.75q0-1.331-.906-2.058q-.795-.637-1.914-.532q-2.262.212-2.615 2.09zM12.25 10q1.313 0 1.477 1.15q.436-.4 1.273-.4q1.75 0 1.75 1.75T15 14.25q-1.633 0-1.742-1.524q-.367.274-1.008.274q-1.5 0-1.5-1.5t1.5-1.5m-5 2q0-1.75 1.75-1.75T10.75 12T9 13.75T7.25 12");
}

</style>
