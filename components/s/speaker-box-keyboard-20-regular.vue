<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yfb3un4vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-box-keyboard-20-regular" /></template>
<style>
.yfb3un4vq {
  fill: currentColor;
  d: path("M16 7a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2zm-4 1a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1zm2 4a2 2 0 1 1 0 4a2 2 0 0 1 0-4m0 1a1 1 0 1 0 0 2a1 1 0 0 0 0-2m1-11a2 2 0 0 1 2 2v2.174A3 3 0 0 0 16 6V4a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h5v1H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm-6 9H5.5a.5.5 0 0 1 0-1H9zm5-1.75a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5M6.498 7a.752.752 0 1 1 0 1.505a.752.752 0 0 1 0-1.505M5.002 4.5a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506m3 0a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506m3 0a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506m3 0a.753.753 0 0 1 .083 1.5h-.166a.753.753 0 0 1 .083-1.5");
}

</style>
