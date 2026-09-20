<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2-dmab_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:volume-mute-sharp" /></template>
<style>
.x2-dmab_d {
  fill: currentColor;
  d: path("M8 14v-4h3.423L15 6.423v11.154L11.423 14z");
}

</style>
