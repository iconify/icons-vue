<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hixlo8gbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-3-bar" /></template>
<style>
.hixlo8gbn {
  fill: currentColor;
  d: path("M2 22L22 2v20zm13-2h5V6.85l-5 5z");
}

</style>
