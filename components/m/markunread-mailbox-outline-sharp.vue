<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjsg4kvxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:markunread-mailbox-outline-sharp" /></template>
<style>
.mjsg4kvxq {
  fill: currentColor;
  d: path("M6.616 14v-4H4v10h16V10H10V9h11v12H3V9h3.616V3h6.5v3.616h-5.5V14zM4 10v4zv10z");
}

</style>
