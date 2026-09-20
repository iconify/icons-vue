<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8pvcjbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scan-text-48-filled" /></template>
<style>
.o8pvcjbmt {
  fill: currentColor;
  d: path("M5.5 31A1.5 1.5 0 0 1 7 32.5v5.25A3.25 3.25 0 0 0 10.25 41h5.25a1.5 1.5 0 0 1 0 3h-5.25A6.25 6.25 0 0 1 4 37.75V32.5A1.5 1.5 0 0 1 5.5 31m37 0a1.5 1.5 0 0 1 1.5 1.5v5.25A6.25 6.25 0 0 1 37.75 44H32.5a1.5 1.5 0 0 1 0-3h5.25A3.25 3.25 0 0 0 41 37.75V32.5a1.5 1.5 0 0 1 1.5-1.5m-17.771 1a1.5 1.5 0 0 1 0 3H15.5a1.5 1.5 0 0 1 0-3zm7.771-9a1.5 1.5 0 0 1 0 3h-17a1.5 1.5 0 0 1 0-3zm-17-19a1.5 1.5 0 0 1 0 3h-5.25A3.25 3.25 0 0 0 7 10.25v5.25a1.5 1.5 0 0 1-3 0v-5.25A6.25 6.25 0 0 1 10.25 4zm17 10a1.5 1.5 0 0 1 0 3h-17a1.5 1.5 0 0 1 0-3zm5.25-10A6.25 6.25 0 0 1 44 10.25v5.25a1.5 1.5 0 0 1-3 0v-5.25A3.25 3.25 0 0 0 37.75 7H32.5a1.5 1.5 0 0 1 0-3z");
}

</style>
