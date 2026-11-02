<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcz1-nbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-fill" /></template>
<style>
.vcz1-nbpa {
  fill: currentColor;
  d: path("M5 2h3v8H6v9a1 1 0 0 0 1 1h2v-3a3 3 0 1 1 6 0v3h2a1 1 0 0 0 1-1v-9h-2V2h3a3 3 0 0 1 3 3v2c0 1.27-.803 2.405-2 2.829V19a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V9.829A3 3 0 0 1 2 7V5a3 3 0 0 1 3-3m9 8h-4V2h4Zm-3 10h2v-3a1 1 0 0 0-2 0Z");
}

</style>
