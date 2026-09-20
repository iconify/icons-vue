<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suybrdybg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:restaurant-outline" /></template>
<style>
.suybrdybg {
  fill: currentColor;
  d: path("M7.5 21.5v-9.034q-1.16-.177-1.965-1.064q-.804-.886-.804-2.171V2.5h1v6.73H7.5V2.5h1v6.73h1.77V2.5h1v6.73q0 1.286-.805 2.172q-.806.887-1.965 1.064V21.5zm9.23 0v-8h-2.46V7q0-1.671.942-2.96q.944-1.29 2.519-1.501V21.5z");
}

</style>
