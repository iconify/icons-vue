<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twl00427y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:source-environment-outline-rounded" /></template>
<style>
.twl00427y {
  fill: currentColor;
  d: path("M2.73 19.346V4.327q0-.206.091-.37q.09-.165.252-.295l3.693-2.577q.212-.143.462-.143t.468.143l3.693 2.577q.161.13.252.295q.09.164.09.37v2.827h8.73q.344 0 .576.232t.232.576v11.384q0 .344-.232.576t-.575.232H3.539q-.344 0-.576-.232q-.232-.233-.232-.576m1-.192h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4 0h3v-3h-3zm0 12h12.538v-11H7.731zm6.884-8H17q.213 0 .356.144t.144.356t-.144.356t-.356.144h-2.384q-.213 0-.357-.144q-.143-.144-.143-.357t.143-.356t.357-.143m0 4H17q.213 0 .356.144t.144.356t-.144.356t-.356.144h-2.384q-.213 0-.357-.144q-.143-.144-.143-.357t.143-.356t.357-.143m-3.03-3.143q-.143.143-.356.143t-.356-.144t-.143-.357t.144-.356t.357-.143t.356.144t.143.357t-.144.356m-.713 3.999q-.143-.144-.143-.357t.144-.356t.357-.143t.356.144t.143.357t-.144.356t-.357.143t-.356-.144");
}

</style>
