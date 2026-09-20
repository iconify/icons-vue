<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7r60qa0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sync-saved-locally-sharp" /></template>
<style>
.h7r60qa0l {
  fill: currentColor;
  d: path("M10.925 14.05L16.6 8.4l-1.425-1.425l-4.25 4.25L8.8 9.1l-1.4 1.4zM1 21v-2h22v2zm1-3V3h20v15z");
}

</style>
