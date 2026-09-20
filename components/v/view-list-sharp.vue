<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sligubb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-list-sharp" /></template>
<style>
.sligubb6p {
  fill: currentColor;
  d: path("M9 20h13v-4H9zM2 8h5V4H2zm0 6h5v-4H2zm0 6h5v-4H2zm7-6h13v-4H9zm0-6h13V4H9z");
}

</style>
