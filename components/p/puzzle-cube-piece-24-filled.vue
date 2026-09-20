<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl2q1k4hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:puzzle-cube-piece-24-filled" /></template>
<style>
.xl2q1k4hp {
  fill: currentColor;
  d: path("M7 21h-.75A3.25 3.25 0 0 1 3 17.75V17h4zm6.5 0h-5v-4h5zm5.5-3.25A3.25 3.25 0 0 1 15.75 21H15v-4h4zM7 15.5H3v-5h4zm6.5 0h-5v-5h5zm5.5 0h-4v-5h4zM7 9H3v-.75A3.25 3.25 0 0 1 6.25 5H7zm6.5 0h-5V5h5zm5.115-7.384a1.25 1.25 0 0 1 1.768 0l2 2a1.25 1.25 0 0 1 0 1.767l-2 1.998a1.25 1.25 0 0 1-1.768 0l-1.999-1.998a1.25 1.25 0 0 1 0-1.768z");
}

</style>
