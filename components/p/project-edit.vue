<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrmokkzss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:project-edit" /></template>
<style>
.zrmokkzss {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7q0-2.75 2.75-2.75h4.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v4.477q-.867-.641-2-.641q-1.414 0-2.414 1l-3.217 3.217q-.658.657-.904 1.555l-.269.989l-.001.002q-.02.076-.037.151H5q-2.75 0-2.75-2.75zm11.901 12.928l.001-.001l.269-.99q.158-.577.581-1l3.218-3.217q.633-.634 1.53-.634t1.53.634q.634.633.634 1.53t-.634 1.53l-3.218 3.218q-.422.423-.998.58l-.992.271q-.875.239-1.518-.403q-.642-.642-.403-1.518m1.447.395q-.009.036.017.062t.063.016l.99-.269q.193-.053.334-.194l3.218-3.218q.194-.195.194-.47t-.194-.47q-.195-.194-.47-.194t-.47.194l-3.218 3.219q-.141.14-.193.332l-.27.991z");
}

</style>
