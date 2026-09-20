<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkv6xcbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:planner-banner-ad-pt-outline-sharp" /></template>
<style>
.lkv6xcbcm {
  fill: currentColor;
  d: path("M5 21V3h14v18zm1-1h12V4H6zm1.73-2.5h8.693l-2.757-3.654l-2.454 3.077l-1.589-1.884zM6 20V4z");
}

</style>
