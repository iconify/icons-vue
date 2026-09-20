<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnqip7_go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sync-saved-locally-off-sharp" /></template>
<style>
.bnqip7_go {
  fill: currentColor;
  d: path("M20.5 23.3L18.2 21H1v-2h15.175l-1-1H2V4.85L.7 3.5l1.4-1.4l19.8 19.8zm1.5-5.45h-1.3l-6.775-6.775L16.6 8.4l-1.425-1.425L12.5 9.65L5.85 3H22z");
}

</style>
