<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhspkg_fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:smart-cart-screen" /></template>
<style>
.zhspkg_fu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 1.75h4q2.5 0 2.5 2.5v1.5q0 1.036-.732 1.768T8.25 8.25H6.461l.375 1.5H20.5q.122 0 .237.038q.07.024.134.06q.065.037.12.085q.056.049.101.107q.046.059.079.125t.052.137q.02.071.025.145t-.004.147t-.032.143l-2 6q-.019.056-.046.108t-.062.099t-.076.089q-.042.041-.089.075q-.048.035-.1.061q-.053.027-.109.045q-.055.018-.113.027t-.117.009H7.75q-.062 0-.124-.01q-.061-.011-.12-.031t-.114-.05t-.104-.068t-.091-.084t-.076-.098t-.059-.11q-.024-.057-.04-.117l-1.5-6l-.608-2.432H4.25q-1.036 0-1.768-.732T1.75 5.75v-1.5q0-1.036.732-1.768T4.25 1.75m2.961 9.5l1.125 4.5h9.623l1.5-4.5zM7 20.249v.002q0 .828.585 1.414q.586.586 1.415.586t1.415-.586t.585-1.416q.001-.827-.585-1.414q-.586-.586-1.415-.586t-1.415.586Q7 19.421 7 20.249m8 .001q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
