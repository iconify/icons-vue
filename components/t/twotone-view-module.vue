<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxblhacsi"/><path class="mnybmzb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-view-module" /></template>
<style>
.lxblhacsi {
  fill: currentColor;
  d: path("M19 11h-3.33V7H19zm-5.33 0h-3.33V7h3.33zM8.33 7v4H5V7zM5 17v-4h3.33v4zm5.33 0v-4h3.33v4zm5.34 0v-4H19v4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.mnybmzb7r {
  fill: currentColor;
  d: path("M3 5v14h18V5zm16 6h-3.33V7H19zm-5.33 0h-3.33V7h3.33zM8.33 7v4H5V7zM5 17v-4h3.33v4zm5.33 0v-4h3.33v4zm5.34 0v-4H19v4z");
}

</style>
