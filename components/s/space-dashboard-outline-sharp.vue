<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkno-zb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:space-dashboard-outline-sharp" /></template>
<style>
.wkno-zb5w {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h6V5H5zm8 0h6v-7h-6zm0-9h6V5h-6z");
}

</style>
