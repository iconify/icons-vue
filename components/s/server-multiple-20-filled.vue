<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sooqw706h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:server-multiple-20-filled" /></template>
<style>
.sooqw706h {
  fill: currentColor;
  d: path("M7.5 2A2.5 2.5 0 0 0 5 4.5v11A2.5 2.5 0 0 0 7.5 18h5a2.5 2.5 0 0 0 2.5-2.5v-11A2.5 2.5 0 0 0 12.5 2zm0 3h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1 0-1M7 12.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m0 2a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5M2 7a2 2 0 0 1 2-2v10.5q0 .255.035.5H4a2 2 0 0 1-2-2zm14 8.5q0 .255-.035.5H16a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2z");
}

</style>
