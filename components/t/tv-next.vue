<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugau3w86o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-next" /></template>
<style>
.ugau3w86o {
  fill: currentColor;
  d: path("m19.5 21.73l-.73-.73l3-3l-3-3l.73-.73L23.23 18zM9 20v-2H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616V12h-4v6h-2.23v2z");
}

</style>
