<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wokdjvb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-navigation" /></template>
<style>
.wokdjvb0b {
  fill: currentColor;
  d: path("m12 7.27l4.28 10.43l-3.47-1.53l-.81-.36l-.81.36l-3.47 1.53zM12 2L4.5 20.29l.71.71L12 18l6.79 3l.71-.71z");
}

</style>
