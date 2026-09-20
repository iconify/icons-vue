<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avehd74dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:planner-banner-ad-pt-sharp" /></template>
<style>
.avehd74dq {
  fill: currentColor;
  d: path("M5 21V3h14v18zm2.73-3.5h8.693l-2.757-3.654l-2.454 3.077l-1.589-1.884z");
}

</style>
