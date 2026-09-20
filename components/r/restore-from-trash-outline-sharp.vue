<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_4h21tut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:restore-from-trash-outline-sharp" /></template>
<style>
.q_4h21tut {
  fill: currentColor;
  d: path("M11.5 15.308h1v-4.689l2.1 2.089l.708-.708L12 8.692L8.692 12l.708.708l2.1-2.089zM6 20V6H5V5h4v-.77h6V5h4v1h-1v14zm1-1h10V6H7zM7 6v13z");
}

</style>
