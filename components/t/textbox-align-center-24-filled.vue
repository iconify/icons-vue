<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3paevnbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-align-center-24-filled" /></template>
<style>
.b3paevnbf {
  fill: currentColor;
  d: path("M5.75 3A2.75 2.75 0 0 0 3 5.75v12.5A2.75 2.75 0 0 0 5.75 21h12.5A2.75 2.75 0 0 0 21 18.25V5.75A2.75 2.75 0 0 0 18.25 3zm1.5 6h9.5a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1 0-1.5m2 4h5.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1 0-1.5");
}

</style>
