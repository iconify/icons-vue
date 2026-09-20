<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t2db0kbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wifi-off-48-regular" /></template>
<style>
.t2db0kbot {
  fill: currentColor;
  d: path("M4.366 4.366a1.25 1.25 0 0 1 1.768 0l37.5 37.5a1.25 1.25 0 0 1-1.768 1.768L27.721 29.488a7.504 7.504 0 0 0-10.686 3.725a1.25 1.25 0 0 1-2.32-.93a10 10 0 0 1 9.52-6.28l-4.775-4.776a14.54 14.54 0 0 0-8.12 6.695A1.25 1.25 0 0 1 9.16 26.7a17.06 17.06 0 0 1 8.355-7.418l-4.036-4.035a21.6 21.6 0 0 0-7.598 7.174a1.25 1.25 0 0 1-2.106-1.349a24.1 24.1 0 0 1 7.876-7.653L4.366 6.134a1.25 1.25 0 0 1 0-1.768M24 33a3 3 0 1 1 0 6a3 3 0 0 1 0-6m-.001-15c6.377 0 11.931 3.512 14.839 8.7a1.25 1.25 0 1 1-2.18 1.222c-2.308-4.117-6.563-6.99-11.514-7.376l-2.492-2.491A17 17 0 0 1 24 18m0-8c8.497 0 15.962 4.416 20.225 11.072a1.25 1.25 0 0 1-2.106 1.349C38.295 16.452 31.608 12.5 24 12.5a21.5 21.5 0 0 0-6.04.861l-1.984-1.984A24 24 0 0 1 24 10");
}

</style>
