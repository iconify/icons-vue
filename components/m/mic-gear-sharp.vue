<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfsm6nb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-gear-sharp" /></template>
<style>
.qfsm6nb5d {
  fill: currentColor;
  d: path("M8.577 12.423Q8 11.846 8 11V5q0-.846.577-1.423T10 3t1.423.577T12 5v6q0 .846-.577 1.423T10 13t-1.423-.577M10.5 20.5h-1v-3.517q-2.35-.216-3.925-1.922T4 11h1q0 2.075 1.463 3.538T10 16q.14 0 .253-.006t.247-.017zm5.23.308l-.107-.885q-.473-.106-.89-.32q-.416-.215-.748-.588l-.835.335l-.538-.815l.688-.577q-.165-.517-.165-1.035t.165-1.034l-.688-.577l.538-.816l.835.335q.313-.373.739-.588t.899-.32l.108-.884h1l.107.884q.473.106.9.32t.739.588l.835-.335l.538.816l-.688.577q.165.517.165 1.034q0 .518-.165 1.035l.688.577l-.538.815l-.835-.334q-.333.373-.749.587t-.89.32l-.107.885zm2.029-2.357q.625-.626.625-1.528t-.625-1.528t-1.528-.626t-1.528.626t-.626 1.528t.626 1.528t1.528.626t1.528-.626");
}

</style>
