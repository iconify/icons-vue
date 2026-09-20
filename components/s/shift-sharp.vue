<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8t_s1bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shift-sharp" /></template>
<style>
.l8t_s1bxo {
  fill: currentColor;
  d: path("M9 20v-7.23H5.115L12 3.576l6.885 9.192H15V20z");
}

</style>
