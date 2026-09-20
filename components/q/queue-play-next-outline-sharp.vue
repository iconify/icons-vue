<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmpnlqbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:queue-play-next-outline-sharp" /></template>
<style>
.wmpnlqbuf {
  fill: currentColor;
  d: path("m19.5 21.73l-.73-.73l3-3l-3-3l.73-.73L23.23 18zM9 20v-2H3V4h18v8h-1V5H4v12h13v1h-2.23v2zm2.5-5.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zM4 17V5z");
}

</style>
