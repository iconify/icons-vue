<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6m2hp1_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:near-me" /></template>
<style>
.f6m2hp1_s {
  fill: currentColor;
  d: path("m13.13 19.346l-2.426-6.088l-6.089-2.466l-.038-.63l14.846-5.624l-5.661 14.808z");
}

</style>
