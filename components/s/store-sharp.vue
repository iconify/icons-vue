<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x68gwys6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:store-sharp" /></template>
<style>
.x68gwys6z {
  fill: currentColor;
  d: path("M4.423 5.5v-1h15.154v1zm.077 14v-6H3.27v-1l1.153-5h15.154l1.154 5v1H19.5v6h-1v-6h-5v6zm1-1h7v-5h-7z");
}

</style>
