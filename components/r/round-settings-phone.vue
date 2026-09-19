<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="qod0rfb7x"/><circle class="ml61terwk"/><circle class="fan5szato"/><path class="l3-01njnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-settings-phone" /></template>
<style>
.fan5szato {
  cx: 20px;
  cy: 10px;
  r: 1px;
  fill: currentColor;
}

.l3-01njnw {
  fill: currentColor;
  d: path("m15.63 14.4l-2.52 2.5c-2.5-1.43-4.57-3.5-6-6l2.5-2.52c.23-.24.33-.57.27-.9L9.13 3.8c-.09-.46-.5-.8-.98-.8H4c-.56 0-1.03.47-1 1.03c.17 2.89 1.05 5.6 2.43 7.97c1.58 2.73 3.85 4.99 6.57 6.57c2.37 1.37 5.08 2.26 7.97 2.43c.56.03 1.03-.44 1.03-1v-4.15c0-.48-.34-.89-.8-.98l-3.67-.73a.99.99 0 0 0-.9.26");
}

.ml61terwk {
  cx: 16px;
  cy: 10px;
  r: 1px;
  fill: currentColor;
}

.qod0rfb7x {
  cx: 12px;
  cy: 10px;
  r: 1px;
  fill: currentColor;
}

</style>
