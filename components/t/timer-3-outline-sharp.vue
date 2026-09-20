<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibfk2gb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:timer-3-outline-sharp" /></template>
<style>
.ibfk2gb2y {
  fill: currentColor;
  d: path("M8 19v-3h6v-2.5H9v-3h5V8H8V5h9v5.5L15.5 12l1.5 1.5V19z");
}

</style>
