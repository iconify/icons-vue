<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f42wdzbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-connected-no-internet-4-bar-sharp" /></template>
<style>
.f42wdzbpu {
  fill: currentColor;
  d: path("M3 21L21 3v4.23h-3.384V21zm17-3.23V9.615h1v8.153zm-.23 3.46v-1.46h1.46v1.46z");
}

</style>
