<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wocqzzb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stock-media-outline-sharp" /></template>
<style>
.wocqzzb8a {
  fill: currentColor;
  d: path("M2 15V2h13v13zm2-2h9V4H4zm4-1.75L6.8 9.6L5 12h7L9.7 9zm6.875 9.875Q14 20.25 14 19t.875-2.125T17 16q.275 0 .513.05t.487.125V11h4v2h-2v6q0 1.25-.875 2.125T17 22t-2.125-.875M4 13V4z");
}

</style>
