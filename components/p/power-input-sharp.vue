<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xeeqhccob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:power-input-sharp" /></template>
<style>
.xeeqhccob {
  fill: currentColor;
  d: path("M2 15v-2h5v2zm0-4V9h19v2zm7 4v-2h5v2zm7 0v-2h5v2z");
}

</style>
