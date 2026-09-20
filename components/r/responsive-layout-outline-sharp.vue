<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbx79ib5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:responsive-layout-outline-sharp" /></template>
<style>
.pbx79ib5v {
  fill: currentColor;
  d: path("M3 21V8h5V3h13v18zm13-2h3V5h-9v3h6zm-6 0h4v-9h-4zm-5 0h3v-9H5zM16 8v2zm0 0");
}

</style>
