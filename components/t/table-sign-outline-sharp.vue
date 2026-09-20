<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0uie3_se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-sign-outline-sharp" /></template>
<style>
.k0uie3_se {
  fill: currentColor;
  d: path("M5 22v-2h6v-2.75q-.45-.275-.725-.725T10 15.5q0-.825.575-1.413T12 13.5q.825 0 1.413.587T14 15.5q0 .575-.275 1.013t-.725.712V20h6v2zm-2-6V2h18v14h-5.025q.05-.5-.012-1.012T15.7 14H19V4H5v10h3.275q-.2.475-.25.988t0 1.012zm4-4h10v-2H7zm0-4h10V6H7z");
}

</style>
