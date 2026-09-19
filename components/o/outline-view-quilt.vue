<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxtd0ebdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-view-quilt" /></template>
<style>
.hxtd0ebdh {
  fill: currentColor;
  d: path("M3 5v14h18V5zm5.33 12H5V7h3.33zm5.34 0h-3.33v-4h3.33zM19 17h-3.33v-4H19zm0-6h-8.67V7H19z");
}

</style>
