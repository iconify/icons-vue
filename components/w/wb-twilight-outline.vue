<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scgptnolz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wb-twilight-outline" /></template>
<style>
.scgptnolz {
  fill: currentColor;
  d: path("m18.35 10.1l-1.4-1.45l2.15-2.1l1.4 1.4zM2 20v-2h20v2zm9-13V4h2v3zm-5.35 3.05L3.55 7.9l1.4-1.4L7.1 8.65zM7.425 14h9.15q-.575-1.35-1.8-2.175T12 11t-2.775.825T7.425 14M5 16q0-2.925 2.038-4.962T12 9t4.963 2.038T19 16zm7-2");
}

</style>
