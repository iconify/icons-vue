<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nif6tdbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-description-28-filled" /></template>
<style>
.nif6tdbtb {
  fill: currentColor;
  d: path("M3 6a1 1 0 0 0 0 2h21.997a1 1 0 1 0 0-2zm0 15a1 1 0 1 0 0 2h14.997a1 1 0 1 0 0-2zm-1-9a1 1 0 0 1 1-1h21.997a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m1 4a1 1 0 1 0 0 2h21.997a1 1 0 1 0 0-2z");
}

</style>
