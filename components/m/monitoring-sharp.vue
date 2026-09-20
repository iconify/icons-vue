<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thl3w8b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitoring-sharp" /></template>
<style>
.thl3w8b5f {
  fill: currentColor;
  d: path("m3 20.5l-.173-.635L4.5 18.213V20.5zm4.5 0v-5.288l1-1V20.5zm4 0v-6.288l1 1.025V20.5zm4 0v-5.263l1-1V20.5zm4 0v-9.288l1-1V20.5zm-16-5.886V13.21l6.5-6.5l4 4l6.5-6.5v1.403l-6.5 6.5l-4-4z");
}

</style>
