<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eylnljznq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:snet-mobile" /></template>
<style>
.eylnljznq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.093 21.45l31.814.027m-13.119-4.311l-.032-6.74L29.69 4.5l2.973 5.83l-.013 6.834M9.174 30.722v-2.285c0-3.972 6.205-3.754 6.205 0v3.505m5.453 1.368v-4.716c0-4.17 6.264-4.146 6.264 0v8.619m5.442 6.287V32.774c0-3.959 3.163-7.307 7.307-7.307");
}

</style>
