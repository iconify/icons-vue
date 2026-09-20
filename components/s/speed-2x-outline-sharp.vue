<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsbtm4uap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-2x-outline-sharp" /></template>
<style>
.tsbtm4uap {
  fill: currentColor;
  d: path("M5.885 16.5v-5h4v-3h-4v-1h5v5h-4v3h4v1zm6.384 0l2.808-4.692L12.5 7.5h1.116l2.019 3.383L17.654 7.5h1.077l-2.558 4.27L19 16.5h-1.115l-2.27-3.786l-2.269 3.786z");
}

</style>
