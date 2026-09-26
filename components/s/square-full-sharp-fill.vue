<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dxh7ddskd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-full-sharp-fill" /></template>
<style>
.dxh7ddskd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM7 6L17 6C17.5523 6 18 6.4477 18 7L18 17C18 17.5523 17.5523 18 17 18L7 18C6.4477 18 6 17.5523 6 17L6 7C6 6.4477 6.4477 6 7 6Z");
}

</style>
