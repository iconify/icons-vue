<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9yoih0yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:star-rate-half-outline-sharp" /></template>
<style>
.q9yoih0yq {
  fill: currentColor;
  d: path("M12 7.9v5.9l2.4 1.85l-.9-3.05l2.25-1.6h-2.8zM7.69 18.346l1.614-5.33L5.115 10h5.216L12 4.462L13.67 10h5.215l-4.189 3.016l1.614 5.33L12 15.07z");
}

</style>
