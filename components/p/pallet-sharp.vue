<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1wl-bcth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pallet-sharp" /></template>
<style>
.d1wl-bcth {
  fill: currentColor;
  d: path("M3.885 19.577v-2h16.23v2h-1.769v-1h-5.461v1h-1.77v-1h-5.46v1zm2.134-4v-12h11.962v12zM9 8.154h6v-1H9z");
}

</style>
