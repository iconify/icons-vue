<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vxa-6bbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scan-text-48-regular" /></template>
<style>
.vxa-6bbkk {
  fill: currentColor;
  d: path("M5.25 31c.69 0 1.25.56 1.25 1.25v5.5a3.75 3.75 0 0 0 3.75 3.75h5.5a1.25 1.25 0 1 1 0 2.5h-5.5A6.25 6.25 0 0 1 4 37.75v-5.5c0-.69.56-1.25 1.25-1.25m37.5 0c.69 0 1.25.56 1.25 1.25v5.5A6.25 6.25 0 0 1 37.75 44h-5.5a1.25 1.25 0 1 1 0-2.5h5.5a3.75 3.75 0 0 0 3.75-3.75v-5.5c0-.69.56-1.25 1.25-1.25m-18 1a1.25 1.25 0 1 1 0 2.5h-9.5a1.25 1.25 0 1 1 0-2.5zm8-9a1.25 1.25 0 1 1 0 2.5h-17.5a1.25 1.25 0 1 1 0-2.5zm-17-19a1.25 1.25 0 1 1 0 2.5h-5.5a3.75 3.75 0 0 0-3.75 3.75v5.5a1.25 1.25 0 1 1-2.5 0v-5.5A6.25 6.25 0 0 1 10.25 4zm22 0A6.25 6.25 0 0 1 44 10.25v5.5a1.25 1.25 0 1 1-2.5 0v-5.5a3.75 3.75 0 0 0-3.75-3.75h-5.5a1.25 1.25 0 1 1 0-2.5zm-5 10a1.25 1.25 0 1 1 0 2.5h-17.5a1.25 1.25 0 1 1 0-2.5z");
}

</style>
