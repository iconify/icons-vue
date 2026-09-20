<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="le9gmbcmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scan-camera-48-filled" /></template>
<style>
.le9gmbcmv {
  fill: currentColor;
  d: path("M5.5 31A1.5 1.5 0 0 1 7 32.5v5.25A3.25 3.25 0 0 0 10.25 41h5.25a1.5 1.5 0 0 1 0 3h-5.25A6.25 6.25 0 0 1 4 37.75V32.5A1.5 1.5 0 0 1 5.5 31m37 0a1.5 1.5 0 0 1 1.5 1.5v5.25A6.25 6.25 0 0 1 37.75 44H32.5a1.5 1.5 0 0 1 0-3h5.25A3.25 3.25 0 0 0 41 37.75V32.5a1.5 1.5 0 0 1 1.5-1.5M25.925 14.503a2.25 2.25 0 0 1 1.94 1.11L28.68 17h2.07A3.25 3.25 0 0 1 34 20.25v9.5A3.25 3.25 0 0 1 30.75 33h-13.5A3.25 3.25 0 0 1 14 29.75v-9.5A3.25 3.25 0 0 1 17.25 17h2.08l.875-1.425a2.25 2.25 0 0 1 1.917-1.072zM24 20a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9m0 1.5a3 3 0 1 1 0 6a3 3 0 0 1 0-6M15.5 4a1.5 1.5 0 0 1 0 3h-5.25A3.25 3.25 0 0 0 7 10.25v5.25a1.5 1.5 0 0 1-3 0v-5.25A6.25 6.25 0 0 1 10.25 4zm22.25 0A6.25 6.25 0 0 1 44 10.25v5.25a1.5 1.5 0 0 1-3 0v-5.25A3.25 3.25 0 0 0 37.75 7H32.5a1.5 1.5 0 0 1 0-3z");
}

</style>
