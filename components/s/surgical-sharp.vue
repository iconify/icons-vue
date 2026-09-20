<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebufe1bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:surgical-sharp" /></template>
<style>
.ebufe1bzn {
  fill: currentColor;
  d: path("M12.4 15.35L8.65 11.6l9.025-9.025l3.75 3.75zM11 21l2-2h9v2zm-5.925 0q-1.15 0-2.213-.45T1 19.3l6.625-6.6L12 17.05L9.75 19.3q-.8.8-1.862 1.25T5.675 21z");
}

</style>
