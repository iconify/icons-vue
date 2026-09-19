<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uao3e3pws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:streetcomplete" /></template>
<style>
.uao3e3pws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.28 5.5h5.44v4.59h4.16v9.17h-4.16v3.3h11l4.59 4.59l-4.59 4.59h-11V44.5h-5.44V31.74h-4.16v-9.18h4.16v-3.3h-11l-4.63-4.58l4.59-4.59h11Zm0 4.59h5.44m0 9.17h-5.44m0 3.3h5.44m.25 9.18h-5.69");
}

</style>
