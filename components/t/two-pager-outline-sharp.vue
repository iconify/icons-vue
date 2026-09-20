<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-hjsyzue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:two-pager-outline-sharp" /></template>
<style>
.j-hjsyzue {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h7.5V6H4zm8.5 0H20V6h-7.5zm-7.115-2.5h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zm8.5 6h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zM11.5 18V6z");
}

</style>
