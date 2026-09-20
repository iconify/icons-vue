<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo_vlhz-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-displays-sharp" /></template>
<style>
.mo_vlhz-z {
  fill: currentColor;
  d: path("M3 15.327V3h14.27v1H4v11.327zM11.52 21v-2H6.77V6.77h15.25V19h-4.77v2z");
}

</style>
