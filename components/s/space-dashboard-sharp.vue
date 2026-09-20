<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3ydfbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:space-dashboard-sharp" /></template>
<style>
.ye3ydfbrz {
  fill: currentColor;
  d: path("M4 20V4h7.5v16zm8.5-9V4H20v7zm7.5 9h-7.5v-8H20z");
}

</style>
