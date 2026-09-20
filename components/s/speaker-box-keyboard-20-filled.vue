<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f320xgbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-box-keyboard-20-filled" /></template>
<style>
.f320xgbqh {
  fill: currentColor;
  d: path("M16 7a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2zm-2 5a2 2 0 1 0 0 4a2 2 0 0 0 0-4m0 1a1 1 0 1 1 0 2a1 1 0 0 1 0-2m1-11a2 2 0 0 1 2 2v2.174A3 3 0 0 0 16 6h-1.915a.753.753 0 1 0-.166 0H12a3 3 0 0 0-3 3v1H5.5a.5.5 0 0 0 0 1H9v2H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm-1 7.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M6.498 7a.753.753 0 1 0 0 1.506a.753.753 0 0 0 0-1.506M5.002 4.5a.752.752 0 1 0 0 1.505a.752.752 0 0 0 0-1.505m3 0a.752.752 0 1 0 0 1.505a.752.752 0 0 0 0-1.505m3 0a.752.752 0 1 0 0 1.505a.752.752 0 0 0 0-1.505");
}

</style>
