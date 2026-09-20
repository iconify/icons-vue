<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyph3bccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-outline-sharp" /></template>
<style>
.iyph3bccs {
  fill: currentColor;
  d: path("m8.277 19.25l-4.461.935l.934-4.462zm0 0L4.75 15.723L16.875 3.598l3.527 3.527zm.2-1.602L19 7.125L16.875 5L6.352 15.523z");
}

</style>
