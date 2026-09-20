<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdy3bxb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-alt-1-bar-outline-sharp" /></template>
<style>
.sdy3bxb_e {
  fill: currentColor;
  d: path("M5 20v-6h3v6z");
}

</style>
