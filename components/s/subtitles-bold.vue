<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="dnkuvmlmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:subtitles-bold" /></template>
<style>
.dnkuvmlmk {
  fill: currentColor;
  d: path("M224 44H32a20 20 0 0 0-20 20v128a20 20 0 0 0 20 20h192a20 20 0 0 0 20-20V64a20 20 0 0 0-20-20m-4 144H36V68h184ZM48 128a12 12 0 0 1 12-12h16a12 12 0 0 1 0 24H60a12 12 0 0 1-12-12m56 0a12 12 0 0 1 12-12h80a12 12 0 0 1 0 24h-80a12 12 0 0 1-12-12m-56 36a12 12 0 0 1 12-12h80a12 12 0 0 1 0 24H60a12 12 0 0 1-12-12m160 0a12 12 0 0 1-12 12h-16a12 12 0 0 1 0-24h16a12 12 0 0 1 12 12");
}

</style>
