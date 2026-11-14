<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io-p27xyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:protected-area-fence" /></template>
<style>
.io-p27xyb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.126 10.425q.537 2.684 3.204 3.305q.084.02.17.02h2.75v7.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-7.75h2.75q.088 0 .173-.02q3.052-.724 3.585-3.815q.513-2.976-1.91-4.667q-1.693-3.677-5.795-3.246q-4.07.429-4.978 4.319q-1.956 1.567-1.449 4.104m16.126 3.119l3.5 1.25q.11.039.202.109t.159.165t.102.205t.035.227V18q0 3.461-4.068 4.478q-.182.045-.364 0Q13.75 21.461 13.75 18v-2.5q0-.116.035-.227q.035-.11.102-.205t.159-.165t.202-.109l3.5-1.25q.122-.044.252-.044t.252.044m-3.002 2.485V18q0 2.217 2.75 2.975q2.75-.758 2.75-2.975v-1.971L18 15.046z");
}

</style>
