<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9_e39bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:privacy-screen-outline-sharp" /></template>
<style>
.k9_e39bvl {
  fill: currentColor;
  d: path("M4 9.6L7.6 6H4Zm0 7L14.575 6H10.4L4 12.425ZM5.4 18H20V6h-2.6ZM2 20V4h20v16Z");
}

</style>
