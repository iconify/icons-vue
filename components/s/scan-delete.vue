<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmnegxbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scan-delete" /></template>
<style>
.cmnegxbbj {
  fill: currentColor;
  d: path("M13 9h5l-5-5zm2.9 12.5l-1.4-1.4l2.1-2.1l-2.1-2.1l1.4-1.4l2.1 2.1l2.1-2.1l1.4 1.4l-2.075 2.1l2.075 2.1l-1.4 1.4l-2.1-2.075zM6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h8l6 6v4.35q-.475-.175-.987-.262T17.975 12q-2.5 0-4.237 1.738T12 17.975q0 1.125.4 2.163T13.55 22z");
}

</style>
