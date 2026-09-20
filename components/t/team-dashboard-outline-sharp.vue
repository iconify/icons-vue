<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzx2q-k9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:team-dashboard-outline-sharp" /></template>
<style>
.zzx2q-k9k {
  fill: currentColor;
  d: path("M4 20V4h16v16zm6.5-1v-6.5H5V19zm1 0H19v-6.5h-7.5zM5 11.5h14V5H5z");
}

</style>
