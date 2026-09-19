<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gztompbxl"/><path class="p2mhp7qbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-cabin" /></template>
<style>
.gztompbxl {
  fill: currentColor;
  d: path("M13.94 7h-3.89L12 5.52zm-6.5 2h9.12L18 10.1v.9H6v-.9zM18 13v2H6v-2zM6 19v-2h12v2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.p2mhp7qbo {
  fill: currentColor;
  d: path("M10 1c0 1.66-1.34 3-3 3c-.55 0-1 .45-1 1H4c0-1.66 1.34-3 3-3c.55 0 1-.45 1-1zm2 2L6 7.58V6H4v3.11L1 11.4l1.21 1.59L4 11.62V21h16v-9.38l1.79 1.36L23 11.4zm1.94 4h-3.89L12 5.52zm-6.5 2h9.12L18 10.1v.9H6v-.9zM18 13v2H6v-2zM6 19v-2h12v2z");
}

</style>
