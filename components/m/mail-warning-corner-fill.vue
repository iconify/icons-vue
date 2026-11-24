<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7fdetbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-warning-corner-fill" /></template>
<style>
.u7fdetbnn {
  fill: currentColor;
  d: path("M3.707 4.292A3 3 0 0 1 5 4h14c.448 0 .889.099 1.293.292L14.586 10H9.414ZM21 12h-5.586l6.294-6.293c.193.404.292.845.292 1.293v4a1 1 0 0 1-1 1M2 17V7c0-.448.099-.889.292-1.293l5.415 5.414A3 3 0 0 0 9.828 12H12v7a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3m17-2v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m-1 5h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

</style>
