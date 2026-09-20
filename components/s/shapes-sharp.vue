<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt4mmab-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shapes-sharp" /></template>
<style>
.qt4mmab-q {
  fill: currentColor;
  d: path("M4.98 13.486Q3.23 11.74 3.23 9.234T4.977 4.98q1.746-1.75 4.251-1.75t4.255 1.746t1.749 4.251t-1.745 4.255t-4.251 1.749t-4.255-1.745m3.79 7.283v-2.78l.23.008q.116.003.23.003q3.655 0 6.212-2.558T18 9.231q0-.115-.003-.231l-.008-.23h2.78v12z");
}

</style>
