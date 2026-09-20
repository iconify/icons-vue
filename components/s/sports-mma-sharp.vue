<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2lh7abvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-mma-sharp" /></template>
<style>
.g2lh7abvt {
  fill: currentColor;
  d: path("M8 19.616v-3.232h8.077v3.231zM7.039 15l-.808-4.05V3.846h10v2.77h1.538v4.296L16.923 15zM9 9.77h4.462V8H9z");
}

</style>
