<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ultpcr1jv"/><path class="r9r3-pbyn"/><path class="yrixav1co"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refresh-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r9r3-pbyn {
  d: path("m15.5 9l3 3l3-3m-7.33 9.127q-.462.163-.943.256q-.482.092-.971.112q-.49.019-.978-.035q-.487-.055-.96-.182q-.257-.069-.508-.158q-.25-.09-.493-.2q-.242-.109-.474-.239q-.233-.129-.454-.277q-.221-.147-.43-.313q-.208-.165-.402-.347t-.373-.379t-.341-.408t-.306-.435t-.269-.458t-.232-.479q-.105-.244-.191-.496q-.085-.252-.15-.51t-.108-.52t-.065-.528T5.5 12");
}

.ultpcr1jv {
  d: path("M9.83 5.873q.462-.163.943-.256q.482-.092.971-.112q.49-.019.978.035q.487.055.96.182q.257.069.508.158q.25.09.493.2q.242.109.474.239q.233.129.454.277q.221.147.43.313q.208.165.402.347t.373.379t.341.408t.306.435t.269.458t.232.479q.105.244.191.496t.15.51q.065.258.108.52q.043.263.065.528T18.5 12");
}

.yrixav1co {
  d: path("m2.5 15l3-3l3 3m-5-11.5l17 17");
}

</style>
