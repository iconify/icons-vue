<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pya37j6aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-1-fill-round" /></template>
<style>
.pya37j6aq {
  fill: currentColor;
  d: path("M12.293 3.293A1 1 0 0 1 14 4v16a1 1 0 0 1-2 0V6.414L8.707 9.707a.999.999 0 1 1-1.414-1.414Z");
}

</style>
