<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbukqtlin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stack-group-sharp" /></template>
<style>
.bbukqtlin {
  fill: currentColor;
  d: path("M9 21v-6H3V3h12v6h6v12z");
}

</style>
