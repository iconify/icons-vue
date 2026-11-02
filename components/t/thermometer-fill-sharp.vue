<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcyi-ivnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thermometer-fill-sharp" /></template>
<style>
.vcyi-ivnk {
  fill: currentColor;
  d: path("M6 11.423V5a3 3 0 1 1 6 0v6.423a5.473 5.473 0 1 1-6 0M19 3a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm-2 3a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2Zm2 5h-4a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2");
}

</style>
