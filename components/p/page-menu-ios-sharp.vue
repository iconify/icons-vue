<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9h19ku1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-menu-ios-sharp" /></template>
<style>
.p9h19ku1c {
  fill: currentColor;
  d: path("M3 21v-2h12v2zm0-4v-2h18v2zm0-4V3h18v10z");
}

</style>
