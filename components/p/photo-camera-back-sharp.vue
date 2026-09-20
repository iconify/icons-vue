<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htuzd5bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-camera-back-sharp" /></template>
<style>
.htuzd5bzy {
  fill: currentColor;
  d: path("M3 20V6h4.573l1.85-2h5.154l1.85 2H21v14zm4.5-3.384h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115z");
}

</style>
