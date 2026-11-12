<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="f0nhpsynn"/><ellipse class="rarrkzbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-rounded-bold-duotone" /></template>
<style>
.f0nhpsynn {
  cx: 12px;
  cy: 6px;
  r: 4px;
  fill: currentColor;
}

.rarrkzbto {
  cx: 12px;
  cy: 17px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 7px;
  ry: 4px;
}

</style>
