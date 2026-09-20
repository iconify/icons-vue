<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddndqqb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-off-sharp" /></template>
<style>
.ddndqqb9g {
  fill: currentColor;
  d: path("M21.325 18.475L5.85 3H22v15.475zm-18.15-15.3v2.8L.7 3.5l1.4-1.4l19.8 19.8l-1.4 1.4l-4.3-4.3H16v2H8v-2H2V3.175z");
}

</style>
