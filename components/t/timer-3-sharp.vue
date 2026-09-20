<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npw2ncbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:timer-3-sharp" /></template>
<style>
.npw2ncbdv {
  fill: currentColor;
  d: path("M8.885 18.116v-1.231h6v-4.27h-5v-1.23h5v-4.27h-6v-1.23h7.23v5.5L15.5 12l.616.616v5.5z");
}

</style>
