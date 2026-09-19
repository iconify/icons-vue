<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic7tbjeiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-propane" /></template>
<style>
.ic7tbjeiy {
  fill: currentColor;
  d: path("M16.75 6H16V3H8v3h-.75C3.97 6 1.1 8.53 1 11.82A6 6 0 0 0 7 18v3h2v-3h6v3h2v-3c3.38 0 6.1-2.79 6-6.18C22.9 8.53 20.03 6 16.75 6M10 5h4v1h-4z");
}

</style>
