<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="iu35e1xme"/><path class="ntr2t_sfw"/><path class="akfxyttyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-system-security-update-warning" /></template>
<style>
.akfxyttyf {
  fill: currentColor;
  d: path("M17 1H7c-1.1 0-1.99.9-1.99 2v18c0 1.1.89 2 1.99 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 17H7V6h10z");
}

.iu35e1xme {
  cx: 12px;
  cy: 16px;
  r: 1px;
  fill: currentColor;
}

.ntr2t_sfw {
  fill: currentColor;
  d: path("M12 13c.55 0 1-.45 1-1V8c0-.55-.45-1-1-1s-1 .45-1 1v4c0 .55.45 1 1 1");
}

</style>
