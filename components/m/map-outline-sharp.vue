<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il8k7c5xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:map-outline-sharp" /></template>
<style>
.il8k7c5xd {
  fill: currentColor;
  d: path("m15 21l-6-2.1l-6 2.325V5.05L9 3l6 2.1l6-2.325V18.95zm-1-2.45V6.85l-4-1.4v11.7zm2 0l3-1V5.7l-3 1.15zM5 18.3l3-1.15V5.45l-3 1zM16 6.85v11.7zm-8-1.4v11.7z");
}

</style>
