<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpmdc32de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-slight-right" /></template>
<style>
.xpmdc32de {
  fill: currentColor;
  d: path("M9.5 19.77v-7.018q0-.323.13-.628t.349-.522L15.6 6h-2.98V5h4.669v4.67h-1V6.688l-5.616 5.596q-.096.096-.134.202t-.039.22v7.062z");
}

</style>
