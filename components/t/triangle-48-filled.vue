<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h19ubbczs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-48-filled" /></template>
<style>
.h19ubbczs {
  fill: currentColor;
  d: path("M20.471 7.228c1.617-2.99 5.916-2.966 7.5.042l15.533 29.502c1.49 2.83-.562 6.23-3.76 6.23H8.255c-3.22 0-5.27-3.44-3.738-6.272z");
}

</style>
