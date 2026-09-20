<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b_rp06bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-row-20-filled" /></template>
<style>
.b_rp06bgq {
  fill: currentColor;
  d: path("M4 3a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zm1 3.5a.5.5 0 0 1 1 0v7a.5.5 0 0 1-1 0zM13 3a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zm.5 3h2a.5.5 0 0 1 .5.5V10a.5.5 0 0 1-.5.5H14V13h1.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5V10a.5.5 0 0 1 .5-.5H15V7h-1.5a.5.5 0 0 1 0-1");
}

</style>
