<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggdisha9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-in-phone-sharp" /></template>
<style>
.ggdisha9s {
  fill: currentColor;
  d: path("M6 22v-7h1v3.5h10v-13H7V9H6V2h12v20zm4-6.692l-.708-.708l2.089-2.1H2.5v-1h8.88L9.293 9.4L10 8.692L13.308 12z");
}

</style>
