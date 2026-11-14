<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_ixryzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:theory" /></template>
<style>
.jn_ixryzu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75Q8.75 1.75 8.75 5q0 1.779.974 2.585l-3.831 7.237Q5.482 14.75 5 14.75q-3.25 0-3.25 3.25T5 21.25q2.85 0 3.201-2.5h7.598q.351 2.5 3.201 2.5q3.25 0 3.25-3.25T19 14.75q-.482 0-.893.072l-3.831-7.237q.974-.806.974-2.585q0-3.25-3.25-3.25m3.799 15.5H8.201q-.17-1.21-.925-1.835l3.831-7.237q.411.072.893.072t.893-.072l3.831 7.237q-.755.625-.925 1.835");
}

</style>
