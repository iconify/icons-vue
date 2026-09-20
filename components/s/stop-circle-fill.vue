<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qhbhvmqla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stop-circle-fill" /></template>
<style>
.qhbhvmqla {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m32 132a4 4 0 0 1-4 4h-56a4 4 0 0 1-4-4v-56a4 4 0 0 1 4-4h56a4 4 0 0 1 4 4Z");
}

</style>
