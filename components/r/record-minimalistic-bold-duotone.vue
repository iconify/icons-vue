<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3x_ug_ff"/><path class="tb35ynitm"/><path class="edwd7ibhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-minimalistic-bold-duotone" /></template>
<style>
.edwd7ibhc {
  fill: currentColor;
  d: path("M6 16H18C16.9856 16 16.0593 15.6224 15.3542 15H8.64582C7.94069 15.6224 7.01445 16 6 16Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.k3x_ug_ff {
  fill: currentColor;
  d: path("M22 12C22 14.2091 20.2091 16 18 16C15.7909 16 14 14.2091 14 12C14 9.79086 15.7909 8 18 8C20.2091 8 22 9.79086 22 12Z");
}

.tb35ynitm {
  fill: currentColor;
  d: path("M10 12C10 14.2091 8.20914 16 6 16C3.79086 16 2 14.2091 2 12C2 9.79086 3.79086 8 6 8C8.20914 8 10 9.79086 10 12Z");
}

</style>
