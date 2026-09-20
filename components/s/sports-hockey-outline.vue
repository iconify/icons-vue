<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cck503lsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sports-hockey-outline" /></template>
<style>
.cck503lsw {
  fill: currentColor;
  d: path("M2 20v-3q0-.425.288-.712T3 16h1v4zm3 0v-4h4l.85-1.95l1.6 3.5l-.85 1.9q-.125.275-.375.413T9.7 20zm15 0v-4h1q.425 0 .713.288T22 17v3zm-1 0h-4.7q-.275 0-.525-.137t-.375-.413L6.35 4H9.7L12 9.2L14.3 4h3.35l-4.05 8.85L15 16h4z");
}

</style>
