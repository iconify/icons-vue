<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_oy41b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-stable-outline-sharp" /></template>
<style>
.f_oy41b1k {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm12.975 0l2.3-8.65L7.075 6l-2.3 8.65zm-1.425-2.45l-8.325-2.3L8.5 8.45l8.325 2.3zM4 18V6z");
}

</style>
