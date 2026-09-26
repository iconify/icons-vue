<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxxz5ibea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-a-24-regular" /></template>
<style>
.xxxz5ibea {
  fill: currentColor;
  d: path("M17.75 2a.75.75 0 1 1 0 1.5H16v17h1.75a.75.75 0 1 1 0 1.5h-5a.75.75 0 0 1 0-1.5h1.75v-17h-1.75a.75.75 0 0 1 0-1.5zM13.5 6.5H5.25A1.75 1.75 0 0 0 3.5 8.25v7.5c0 .966.784 1.75 1.75 1.75h8.25V19H5.25A3.25 3.25 0 0 1 2 15.75v-7.5A3.25 3.25 0 0 1 5.25 5h8.25zM18.75 5A3.25 3.25 0 0 1 22 8.25v7.5A3.25 3.25 0 0 1 18.75 19H17v-1.5h1.75a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75H17V5zM9 7.5c.292 0 .558.17.68.435l3.25 7a.75.75 0 0 1-1.36.63l-.96-2.065H7.39l-.96 2.065a.75.75 0 0 1-1.36-.63l3.25-7A.75.75 0 0 1 9 7.5M8.086 12h1.828L9 10.031z");
}

</style>
