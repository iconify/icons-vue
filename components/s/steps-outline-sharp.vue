<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt3yglncp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:steps-outline-sharp" /></template>
<style>
.wt3yglncp {
  fill: currentColor;
  d: path("M18.4 20h1.325L20 18.425l-4.875-4.875L13.35 8.2l-3.325.75L9 7.975v-3.35l-.7-.35L4.4 9.5h3zm-5.025 0H15.5l-8.9-8.5H4.05zm-.75 2L.675 11.15L7.7 1.725l3.3 1.65v3.35l3.675-.95l2.2 6.675L22 17.575L21.25 22z");
}

</style>
