<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6tpxqbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scanner-sharp" /></template>
<style>
.d6tpxqbcu {
  fill: currentColor;
  d: path("M17.985 13L4.846 8.246l.316-.938L20 12.708V19H4v-6zm-7.831 3.5H17.5v-1h-7.346zm-3.923.27h1.538v-1.54H6.231z");
}

</style>
