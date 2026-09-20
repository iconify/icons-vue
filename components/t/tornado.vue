<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt80416qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tornado" /></template>
<style>
.kt80416qa {
  fill: currentColor;
  d: path("M1 3h22l-2.9 5H3.9zm4.05 7h13.9l-1.75 3H6.8zm2.9 5h8.1L12 22z");
}

</style>
