<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex8ivmb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thermostat-carbon-outline-sharp" /></template>
<style>
.ex8ivmb5t {
  fill: currentColor;
  d: path("M12 21.377L2.623 12L12 2.623L21.377 12zM12 20l8-8l-8-8l-8 8zm0-8");
}

</style>
