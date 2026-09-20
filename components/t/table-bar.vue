<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld3vd4jzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-bar" /></template>
<style>
.ld3vd4jzq {
  fill: currentColor;
  d: path("m6 20l1.5-3.75q.225-.575.725-.913T9.35 15H11v-4.025Q7.175 10.85 4.587 9.85T2 7.5q0-1.45 2.925-2.475T12 4q4.175 0 7.088 1.025T22 7.5q0 1.35-2.588 2.35T13 10.975V15h1.65q.6 0 1.113.338t.737.912L18 20h-2l-1.2-3H9.2L8 20z");
}

</style>
