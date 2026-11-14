<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3df2t8by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-bed" /></template>
<style>
.d3df2t8by {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10.999q.001-2.898 3.132-4.876Q7.848 4.25 12 4.25t7.118 1.873Q22.25 8.101 22.25 11v3q0 2.899-3.132 4.877Q16.152 20.75 12 20.75t-7.118-1.873Q1.75 16.899 1.75 14zm4.5-.749q0 3.25 5.75 3.25t5.75-3.25T12 7t-5.75 3.25m-2.941 4.382q.32 1.679 2.374 2.977Q8.282 19.25 12 19.25t6.317-1.641q2.054-1.298 2.374-2.977q-.651.662-1.573 1.245Q16.152 17.75 12 17.75t-7.118-1.873q-.922-.583-1.573-1.245");
}

</style>
