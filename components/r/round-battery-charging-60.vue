<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym6u0fbtt"/><path class="r1_dgtbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-battery-charging-60" /></template>
<style>
.r1_dgtbaa {
  fill: currentColor;
  d: path("M13 12.5h1.17c.38 0 .62.4.44.74l-2.67 5c-.24.45-.94.28-.94-.24v-3.5H9.83a.5.5 0 0 1-.44-.74L10.87 11H7v9.67C7 21.4 7.6 22 8.33 22h7.33c.74 0 1.34-.6 1.34-1.33V11h-4z");
}

.ym6u0fbtt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M15.67 4H14V3c0-.55-.45-1-1-1h-2c-.55 0-1 .45-1 1v1H8.33C7.6 4 7 4.6 7 5.33V11h3.87l1.19-2.24c.24-.45.94-.28.94.24v2h4V5.33C17 4.6 16.4 4 15.67 4");
}

</style>
