<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="myvtwd4ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nuinvest" /></template>
<style>
.myvtwd4ta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 14.007v11.248c0 4.083-2.857 7.37-6.406 7.37s-6.406-3.287-6.406-7.37V14.007h-4.85v13.025c0 4.084 2.857 7.37 6.406 7.37s6.406-3.286 6.406-7.37V14.006zm-39 19.985V22.744c0-4.083 2.858-7.37 6.407-7.37s6.405 3.287 6.405 7.37v11.248h4.85V20.968c0-4.084-2.857-7.37-6.406-7.37s-6.406 3.286-6.406 7.37v13.026z");
}

</style>
