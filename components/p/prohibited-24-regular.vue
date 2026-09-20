<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhixp0bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-24-regular" /></template>
<style>
.fhixp0bjm {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2m6.517 4.543L6.543 18.517A8.5 8.5 0 0 0 18.517 6.543M12 3.5a8.5 8.5 0 0 0-6.517 13.957L17.457 5.483A8.47 8.47 0 0 0 12 3.5");
}

</style>
