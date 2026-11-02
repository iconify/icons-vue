<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl2oq5f1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-fill-sharp" /></template>
<style>
.jl2oq5f1x {
  fill: currentColor;
  d: path("m7.086 15.5l-2.793-2.793a.999.999 0 1 1 1.414-1.414L7 12.586L17.293 2.293A1 1 0 0 1 18 2h3a1 1 0 0 1 1 1v3c0 .265-.105.52-.293.707L11.414 17l1.293 1.293a.999.999 0 1 1-1.414 1.414L8.5 16.914L5.414 20l.293.293a.999.999 0 1 1-1.414 1.414l-2-2a1 1 0 0 1 1.414-1.414l.293.293Z");
}

</style>
