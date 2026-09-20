<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlha389cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:waterfall-chart-outline-sharp" /></template>
<style>
.hlha389cu {
  fill: currentColor;
  d: path("M4 19v-4.712h1.923V19zm4.673-5.577V9.635h1.943v3.788zm4.693-4.654V5h1.942v3.77zM18.058 19V5H20v14z");
}

</style>
