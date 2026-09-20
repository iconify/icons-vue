<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7co_q-fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-rotate-90-24-regular" /></template>
<style>
.v7co_q-fd {
  fill: currentColor;
  d: path("M8 17.75a.75.75 0 0 1-1.5 0v-9a.75.75 0 0 1 1.5 0zm6.78-15.03a.75.75 0 0 1 .073.976l-.073.084l-2 2a.75.75 0 0 1-.976.073l-.084-.073l-2-2a.75.75 0 0 1 .976-1.133l.084.073l1.47 1.47l1.47-1.47a.75.75 0 0 1 1.06 0M13 20.75a.75.75 0 0 1-1.5 0v-12a.75.75 0 0 1 1.5 0zm5-3a.75.75 0 0 1-1.5 0v-9a.75.75 0 0 1 1.5 0z");
}

</style>
