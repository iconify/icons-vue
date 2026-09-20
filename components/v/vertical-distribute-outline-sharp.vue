<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk5g6cc_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-distribute-outline-sharp" /></template>
<style>
.bk5g6cc_t {
  fill: currentColor;
  d: path("M2 22v-2h20v2zm5-8.5v-3h10v3zM2 4V2h20v2z");
}

</style>
