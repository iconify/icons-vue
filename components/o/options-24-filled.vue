<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfu-9807j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:options-24-filled" /></template>
<style>
.jfu-9807j {
  fill: currentColor;
  d: path("M8.75 14.5a3.25 3.25 0 0 1 3.163 2.5h9.337a.75.75 0 0 1 .102 1.493l-.102.007l-9.337.001a3.251 3.251 0 0 1-6.326 0L2.75 18.5a.75.75 0 0 1-.102-1.493L2.75 17h2.837a3.25 3.25 0 0 1 3.163-2.5M15.25 3a3.25 3.25 0 0 1 3.163 2.5h2.837a.75.75 0 0 1 .102 1.493L21.25 7l-2.837.001a3.252 3.252 0 0 1-6.326 0L2.75 7a.75.75 0 0 1-.102-1.493L2.75 5.5h9.337A3.25 3.25 0 0 1 15.25 3");
}

</style>
