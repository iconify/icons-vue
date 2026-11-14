<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ijtdzetvo"/><path class="hpazl-2_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meal-plan-cart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hpazl-2_k {
  d: path("M7.2 4.5h9.1a1.75 1.75 0 0 1 1.705 2.144l-.692 3A1.75 1.75 0 0 1 15.608 11H7.892a1.75 1.75 0 0 1-1.705-1.356l-.692-3A1.75 1.75 0 0 1 7.2 4.5M6 15.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6.883-.58q-.042-.102-.099-.196q-.058-.095-.128-.18t-.152-.158t-.173-.135t-.192-.108t-.205-.079t-.215-.048T11.5 14q-.074 0-.147.007t-.146.022q-.072.014-.142.036q-.071.021-.139.049t-.133.063t-.126.076q-.062.041-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126t-.063.133t-.049.139q-.022.07-.036.142q-.015.073-.022.146T10 15.5t.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126t.087.119t.099.109t.109.099q.057.046.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T11.5 17q.374 0 .705-.176M16.75 15.5h2.5A1.75 1.75 0 0 1 21 17.25v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.5v-2.25a1.75 1.75 0 0 1 1.75-1.75M15 17.75h6m-4.25-3.25V16m2.5-1.5V16");
}

.ijtdzetvo {
  d: path("M2.5 2h2l2 9");
}

</style>
