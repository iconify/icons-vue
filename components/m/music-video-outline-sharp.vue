<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixgo1ab3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:music-video-outline-sharp" /></template>
<style>
.ixgo1ab3s {
  fill: currentColor;
  d: path("M12.275 16.275Q13 15.55 13 14.5V9h3V7h-4v5.5q-.325-.225-.7-.363T10.5 12q-1.05 0-1.775.725T8 14.5t.725 1.775T10.5 17t1.775-.725M2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
