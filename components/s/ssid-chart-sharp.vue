<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avajqr5jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ssid-chart-sharp" /></template>
<style>
.avajqr5jh {
  fill: currentColor;
  d: path("m12 21l-6.2-6L3 17v-2.45l3-2.15l6.125 5.95L16.3 15H21v2h-4zm0-9L7.625 7.625L3 11V8.525L7.825 5L12.2 9.375L21 3v2.475z");
}

</style>
