<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkeawxbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-percentage" /></template>
<style>
.fkeawxbbj {
  fill: currentColor;
  d: path("m18.501 3.5l-15 15.001l1.996 1.996l15-15zM17.003 14a3 3 0 1 1-.006 6a3 3 0 0 1 .006-6M17 16a1 1 0 1 0 0 2a1 1 0 0 0 0-2M7.003 4a3 3 0 1 1-.006 6a3 3 0 0 1 .006-6M7 6a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
