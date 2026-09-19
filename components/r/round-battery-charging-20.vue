<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3wk_-iwq"/><path class="br-svt6hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-battery-charging-20" /></template>
<style>
.br-svt6hl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M15.67 4H14V3c0-.55-.45-1-1-1h-2c-.55 0-1 .45-1 1v1H8.33C7.6 4 7 4.6 7 5.33V17h4v-2.5H9.83a.5.5 0 0 1-.44-.74l2.67-5c.24-.45.94-.28.94.24v3.5h1.17c.38 0 .62.4.44.74L12.6 17H17V5.33C17 4.6 16.4 4 15.67 4");
}

.s3wk_-iwq {
  fill: currentColor;
  d: path("M11.94 18.24c-.24.45-.94.28-.94-.24v-1H7v3.67C7 21.4 7.6 22 8.33 22h7.33c.74 0 1.34-.6 1.34-1.33V17h-4.4z");
}

</style>
