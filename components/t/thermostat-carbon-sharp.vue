<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpmkb9brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermostat-carbon-sharp" /></template>
<style>
.hpmkb9brn {
  fill: currentColor;
  d: path("M12 21.377L2.623 12L12 2.623L21.377 12z");
}

</style>
