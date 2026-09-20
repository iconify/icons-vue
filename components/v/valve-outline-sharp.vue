<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voyalzodh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:valve-outline-sharp" /></template>
<style>
.voyalzodh {
  fill: currentColor;
  d: path("M11 8V5H7V3h10v2h-4v3zM4 21v-8h2v1h3v-3H8V9h8v2h-1v3h3v-1h2v8h-2v-1H6v1zm2-3h12v-2h-5v-5h-2v5H6zm6 0");
}

</style>
