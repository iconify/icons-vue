<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjwmxqc8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:tablet-android" /></template>
<style>
.mjwmxqc8i {
  fill: currentColor;
  d: path("M18 0H6C4.34 0 3 1.34 3 3v18c0 1.66 1.34 3 3 3h12c1.66 0 3-1.34 3-3V3c0-1.66-1.34-3-3-3m-4 22h-4v-1h4zm5.25-3H4.75V3h14.5z");
}

</style>
