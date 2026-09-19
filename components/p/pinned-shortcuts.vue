<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r4vn_ykdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pinned-shortcuts" /></template>
<style>
.r4vn_ykdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.979 4.5h19.797v4.092h-2.029v15.32l4.058 3.988v3.918H25.522V43.5h-3.253V31.818H12.195v-4.023l3.813-3.813V8.593h-2.029z");
}

</style>
