<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9azcgbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scan-camera-48-regular" /></template>
<style>
.k9azcgbjk {
  fill: currentColor;
  d: path("M5.25 31c.69 0 1.25.56 1.25 1.25v5.5a3.75 3.75 0 0 0 3.75 3.75h5.5a1.25 1.25 0 1 1 0 2.5h-5.5A6.25 6.25 0 0 1 4 37.75v-5.5c0-.69.56-1.25 1.25-1.25m37.5 0c.69 0 1.25.56 1.25 1.25v5.5A6.25 6.25 0 0 1 37.75 44h-5.5a1.25 1.25 0 1 1 0-2.5h5.5a3.75 3.75 0 0 0 3.75-3.75v-5.5c0-.69.56-1.25 1.25-1.25M25.925 14.503a2.25 2.25 0 0 1 1.94 1.11L28.68 17h2.07A3.25 3.25 0 0 1 34 20.25v9.5A3.25 3.25 0 0 1 30.75 33h-13.5A3.25 3.25 0 0 1 14 29.75v-9.5A3.25 3.25 0 0 1 17.25 17h2.08l.875-1.425a2.25 2.25 0 0 1 1.917-1.072zM24 20a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9m0 1.5a3 3 0 1 1 0 6a3 3 0 0 1 0-6M15.75 4a1.25 1.25 0 1 1 0 2.5h-5.5a3.75 3.75 0 0 0-3.75 3.75v5.5a1.25 1.25 0 1 1-2.5 0v-5.5A6.25 6.25 0 0 1 10.25 4zm22 0A6.25 6.25 0 0 1 44 10.25v5.5a1.25 1.25 0 1 1-2.5 0v-5.5a3.75 3.75 0 0 0-3.75-3.75h-5.5a1.25 1.25 0 1 1 0-2.5z");
}

</style>
