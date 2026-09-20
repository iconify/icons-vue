<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyseybc1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mouse-outline-sharp" /></template>
<style>
.vyseybc1w {
  fill: currentColor;
  d: path("M12 22q-2.9 0-4.95-2.05T5 15V9q0-2.9 2.05-4.95T12 2t4.95 2.05T19 9v6q0 2.9-2.05 4.95T12 22m1-13h4q0-1.8-1.137-3.175T13 4.1zM7 9h4V4.1q-1.725.35-2.863 1.725T7 9m5 11q2.075 0 3.538-1.463T17 15v-4H7v4q0 2.075 1.463 3.538T12 20m0-9");
}

</style>
