<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4nkphb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stacked-email-sharp" /></template>
<style>
.l4nkphb8b {
  fill: currentColor;
  d: path("M5 16.77v-13h17v13zm-3 3V8.653h1v10.115h15.385v1zm11.5-8.283L21 5.943V4.77l-7.5 5.543L6 4.769v1.175z");
}

</style>
