<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4zzrzb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:padding-outline-sharp" /></template>
<style>
.d4zzrzb5l {
  fill: currentColor;
  d: path("M7 9h2V7H7zm4 0h2V7h-2zm4 0h2V7h-2zM3 21V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
