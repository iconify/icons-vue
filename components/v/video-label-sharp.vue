<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8be6abhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-label-sharp" /></template>
<style>
.k8be6abhw {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-5h16V6H4z");
}

</style>
