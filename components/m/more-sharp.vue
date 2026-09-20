<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auxidabvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:more-sharp" /></template>
<style>
.auxidabvy {
  fill: currentColor;
  d: path("M8.366 19L3 12l5.366-7H21v14zm.75-6.23h1.538v-1.54H9.116zm3.5 0h1.538v-1.54h-1.538zm3.5 0h1.538v-1.54h-1.538z");
}

</style>
