<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz43wjbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-outline-sharp" /></template>
<style>
.uz43wjbwe {
  fill: currentColor;
  d: path("M4 18h16v-8h-7V6H4zm-1 1V5h18v14zm1-1V6z");
}

</style>
