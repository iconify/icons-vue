<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_td7q6nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-gift-indonesia" /></template>
<style>
.q_td7q6nm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 20.76V40.5a2 2 0 0 1-2 2h-29a2 2 0 0 1-2-2V20.76m-2-6.37h37v6.369h-37zm18.5 0c-5.748-8.874-9.112-10.892-12.244-7c-3.27 4.064 4.029 7 12.244 7m0 0l-5.201-2.649M24 14.39c5.748-8.874 9.112-10.892 12.244-7c3.27 4.064-4.029 7-12.244 7m0 0l5.201-2.649");
}

</style>
