<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i21pgzaww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-weekend" /></template>
<style>
.i21pgzaww {
  fill: currentColor;
  d: path("M6 9.03V14h12V9.03h2V5H4v4.03zM19 15H5v-4.97H1V19h22v-8.97h-4z");
}

</style>
