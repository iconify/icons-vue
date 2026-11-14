<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8yxnmmzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pool-rack" /></template>
<style>
.i8yxnmmzn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.118 18.564q.975 1.686 2.922 1.686h9.92q1.947 0 2.922-1.686t.003-3.373l-4.96-8.614Q13.951 4.886 12 4.886T9.075 6.577l-4.96 8.614q-.972 1.687.003 3.373M9.75 10.5q0-2.25 2.25-2.25t2.25 2.25T12 12.75T9.75 10.5M7 15.25Q7 13 9.25 13t2.25 2.25t-2.25 2.25T7 15.25M14.75 13Q17 13 17 15.25t-2.25 2.25t-2.25-2.25T14.75 13");
}

</style>
