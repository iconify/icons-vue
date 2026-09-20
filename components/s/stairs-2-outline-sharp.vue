<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thrpz258i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stairs-2-outline-sharp" /></template>
<style>
.thrpz258i {
  fill: currentColor;
  d: path("M3 18v-1h5.664v-5.5h5.663V6H21v1h-5.663v5.5H9.673V18z");
}

</style>
