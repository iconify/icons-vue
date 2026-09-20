<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkh5csbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mintmark-sharp" /></template>
<style>
.xkh5csbxx {
  fill: currentColor;
  d: path("M13.385 20.5v-1h5.292l-5.292-5.292v-1.416l6 6V13.5h1v7zm-6.77-4v-1h-3v-1h6v-4h-6v-6h3v-1h1v1h3v1h-6v4h6v6h-3v1z");
}

</style>
