<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu8gwy0th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-1-bar-outline" /></template>
<style>
.nu8gwy0th {
  fill: currentColor;
  d: path("M2 22L22 2v20zm8-2h10V6.85l-10 10z");
}

</style>
