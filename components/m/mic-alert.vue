<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nghpqb33s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-alert" /></template>
<style>
.nghpqb33s {
  fill: currentColor;
  d: path("M8.577 12.423Q8 11.846 8 11V5q0-.846.577-1.423T10 3t1.423.577T12 5v6q0 .846-.577 1.423T10 13t-1.423-.577M10.5 20.5h-1v-3.517q-2.35-.216-3.925-1.922T4 11h1q0 2.075 1.463 3.538T10 16q.14 0 .253-.006t.247-.017zm5.73-.923q.2 0 .332-.13t.13-.332t-.13-.33t-.331-.131t-.331.13q-.13.132-.13.332t.13.33t.33.131m-.384-1.923h.77v-3.231h-.77zm-2.45 2.181Q12.23 18.672 12.23 17t1.164-2.835T16.231 13t2.835 1.165T20.231 17t-1.165 2.836T16.231 21t-2.836-1.164");
}

</style>
