<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jer1ikdxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sync-saved-locally-off-outline-sharp" /></template>
<style>
.jer1ikdxs {
  fill: currentColor;
  d: path("M20.7 17.85L18.85 16H20V5H7.85l-2-2H22v14.85zm-.2 5.45L18.2 21H1v-2h15.175l-1-1H2V4.85L.7 3.5l1.4-1.4l19.8 19.8zM13.15 16L4 6.825V16zm-.65-6.35l2.675-2.675L16.6 8.4l-2.675 2.675z");
}

</style>
