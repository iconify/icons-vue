<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcsm-ac7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-collections" /></template>
<style>
.rcsm-ac7i {
  fill: currentColor;
  d: path("M22 18V2H6v16zm-11-6l2.03 2.71L16 11l4 5H8zM2 6v16h16v-2H4V6z");
}

</style>
