<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiaypfbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:privacy-screen-sharp" /></template>
<style>
.xiaypfbxd {
  fill: currentColor;
  d: path("M2 11.6L9.6 4H2Zm0 7L16.575 4H12.4L2 14.425ZM3.4 20H22V4h-2.6Z");
}

</style>
