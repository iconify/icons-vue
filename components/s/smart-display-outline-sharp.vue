<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovw0sympn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:smart-display-outline-sharp" /></template>
<style>
.ovw0sympn {
  fill: currentColor;
  d: path("m9.5 16.5l7-4.5l-7-4.5zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
