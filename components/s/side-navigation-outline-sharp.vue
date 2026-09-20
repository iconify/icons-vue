<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f24-01b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:side-navigation-outline-sharp" /></template>
<style>
.f24-01b9t {
  fill: currentColor;
  d: path("M3 21V3h18v18zm9-2h7V5h-7z");
}

</style>
