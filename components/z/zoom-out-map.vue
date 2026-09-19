<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svcxhacqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:zoom-out-map" /></template>
<style>
.svcxhacqc {
  fill: currentColor;
  d: path("m15 3l2.3 2.3l-2.89 2.87l1.42 1.42L18.7 6.7L21 9V3zM3 9l2.3-2.3l2.87 2.89l1.42-1.42L6.7 5.3L9 3H3zm6 12l-2.3-2.3l2.89-2.87l-1.42-1.42L5.3 17.3L3 15v6zm12-6l-2.3 2.3l-2.87-2.89l-1.42 1.42l2.89 2.87L15 21h6z");
}

</style>
