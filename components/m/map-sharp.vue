<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccxuw6b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map-sharp" /></template>
<style>
.ccxuw6b-p {
  fill: currentColor;
  d: path("m15 19.923l-6-2.1l-5 1.94V5.782l5-1.704l6 2.1l5-1.94v14.04zm-.5-1.22v-11.7l-5-1.745v11.7z");
}

</style>
