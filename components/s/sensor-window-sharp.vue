<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4djlzbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sensor-window-sharp" /></template>
<style>
.m4djlzbhc {
  fill: currentColor;
  d: path("M5 20.98V3.02h14v17.96zm1.77-9.615h3.73v-.769h3v.77h3.73V4.712H6.77zm0 1v6.924h10.46v-6.924zM6 4.02v15.962h12V4.019z");
}

</style>
