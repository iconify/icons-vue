<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzlg5271i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stone-cairn" /></template>
<style>
.uzlg5271i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 4q0-.769.355-1.302Q9.404 1.5 12 1.5q3.75 0 3.75 2.5q0 .85-.433 1.411Q17.5 6.11 17.5 8q0 1.258-.967 1.989q2.717.771 2.717 2.761q0 1.575-1.702 2.386q.356.096.694.205q3.01.974 3.008 2.658q.002 1.686-3.008 2.66q-2.602.842-6.242.842t-6.242-.842q-3.008-.974-3.008-2.658v-.002q0-1.684 3.008-2.658q.338-.109.694-.205q-1.702-.811-1.702-2.386q0-1.99 2.717-2.761Q6.5 9.258 6.5 8q0-1.89 2.183-2.589Q8.25 4.85 8.25 4");
}

</style>
