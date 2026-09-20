<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1_lncb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-1-bar-outline-rounded" /></template>
<style>
.n1_lncb9m {
  fill: currentColor;
  d: path("M4.425 22q-.45 0-.737-.3T3.4 21q0-.2.075-.375T3.7 20.3L20.3 3.7q.15-.15.325-.225T21 3.4q.4 0 .7.287t.3.738V20.5q0 .625-.437 1.063T20.5 22zM10 20h10V6.85l-10 10z");
}

</style>
