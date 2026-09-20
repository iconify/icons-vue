<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqtg3_b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:picture-in-picture-small-outline-sharp" /></template>
<style>
.eqtg3_b2j {
  fill: currentColor;
  d: path("M2 20v-2h18V4h2v16zm8-4v-6h8v6z");
}

</style>
