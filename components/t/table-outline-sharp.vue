<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z92hhokhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-outline-sharp" /></template>
<style>
.z92hhokhb {
  fill: currentColor;
  d: path("M4 20V4h16v16zm7.5-5.596H5V19h6.5zm1 0V19H19v-4.596zm-1-1V8.769H5v4.635zm1 0H19V8.769h-6.5zM5 7.769h14V5H5z");
}

</style>
