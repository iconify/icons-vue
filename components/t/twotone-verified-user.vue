<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r94bso3my"/><path class="hrhe-eb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-verified-user" /></template>
<style>
.hrhe-eb_m {
  fill: currentColor;
  d: path("M5 6.3V11c0 4.52 2.98 8.69 7 9.93c4.02-1.23 7-5.41 7-9.93V6.3l-7-3.11zM18 9l-8 8l-4-4l1.41-1.41L10 14.17l6.59-6.59z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r94bso3my {
  fill: currentColor;
  d: path("M12 1L3 5v6c0 5.55 3.84 10.74 9 12c5.16-1.26 9-6.45 9-12V5zm7 10c0 4.52-2.98 8.69-7 9.93c-4.02-1.24-7-5.41-7-9.93V6.3l7-3.11l7 3.11zm-11.59.59L6 13l4 4l8-8l-1.41-1.42L10 14.17z");
}

</style>
