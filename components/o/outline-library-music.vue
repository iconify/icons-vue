<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgtor3p_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-library-music" /></template>
<style>
.cgtor3p_u {
  fill: currentColor;
  d: path("M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 14H8V4h12zm-7.5-1a2.5 2.5 0 0 0 2.5-2.5V7h3V5h-4v5.51c-.42-.32-.93-.51-1.5-.51a2.5 2.5 0 0 0 0 5M4 6H2v14c0 1.1.9 2 2 2h14v-2H4z");
}

</style>
