<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fon7tkm9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-android-16-regular" /></template>
<style>
.fon7tkm9l {
  fill: currentColor;
  d: path("M12 3a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-2 1a2 2 0 1 1 .491 1.313L5.956 7.581a2 2 0 0 1 0 .838l4.535 2.268a2 2 0 1 1-.447.894L5.508 9.313a2 2 0 1 1 0-2.627l4.536-2.267A2 2 0 0 1 10 4M3 8a1 1 0 1 0 2 0a1 1 0 0 0-2 0m8 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
