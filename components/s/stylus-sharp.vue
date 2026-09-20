<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw2qgsdsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-sharp" /></template>
<style>
.yw2qgsdsm {
  fill: currentColor;
  d: path("m8.162 19.273l-4.347.912l.912-4.346zm.76-.648l-3.547-3.546l11.5-11.481l3.527 3.527z");
}

</style>
