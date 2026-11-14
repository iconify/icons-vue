<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ijtdzetvo"/><path class="b2a00dd5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meal-plan-cart" /></template>
<style>
.b2a00dd5v {
  d: path("M5 4.5h13.5L17 11H6.5Zm1 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.19-1.332Q11.865 14 11.5 14q-.074 0-.147.007t-.146.022q-.072.014-.142.036q-.071.021-.139.049t-.133.063t-.126.076q-.062.041-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126t-.063.133t-.049.139q-.022.07-.036.142q-.015.073-.022.146T10 15.5t.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126t.087.119t.099.109t.109.099q.057.046.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T11.5 17q.374 0 .705-.176M15 15.5h6v5.75h-6Zm0 2.25h6m-4.25-3.25V16m2.5-1.5V16");
}

.ijtdzetvo {
  d: path("M2.5 2h2l2 9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
