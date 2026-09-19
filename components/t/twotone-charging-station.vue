<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aptzl1bkp"/><path class="lo-7uxb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-charging-station" /></template>
<style>
.aptzl1bkp {
  fill: currentColor;
  d: path("M17 3v1H7V3zm0 17H7v1h10z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.lo-7uxb5a {
  fill: currentColor;
  d: path("m14.5 11l-3 6v-4h-2l3-6v4zM17 3H7v1h10zm0 17H7v1h10zm0-19c1.1 0 2 .9 2 2v18c0 1.1-.9 2-2 2H7c-1.1 0-2-.9-2-2V3c0-1.1.9-2 2-2zM7 18h10V6H7z");
}

</style>
