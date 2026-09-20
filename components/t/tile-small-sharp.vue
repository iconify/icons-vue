<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj8_t7fgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tile-small-sharp" /></template>
<style>
.xj8_t7fgp {
  fill: currentColor;
  d: path("M4 18v-4.808h6.808V18zm9.192 0v-4.808H20V18zM4 10.808V6h6.808v4.808zm9.192 0V6H20v4.808z");
}

</style>
