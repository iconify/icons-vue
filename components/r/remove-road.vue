<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjglm_bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:remove-road" /></template>
<style>
.hjglm_bnh {
  fill: currentColor;
  d: path("M17.5 12.962V4.5h1v8.462zm-12 6.769V4.5h1v15.23zm6-12V4.5h1v3.23zm0 6V10.5h1v3.23zm0 6V16.5h1v3.23zm3.694 1.094l2.106-2.106l-2.125-2.119l.714-.713l2.115 2.125l2.115-2.125l.708.713l-2.106 2.116l2.1 2.115l-.702.708l-2.111-2.125l-2.125 2.125z");
}

</style>
