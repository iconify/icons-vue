<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnsluqb9w"/><path class="ehfo_abad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-subtitles-off" /></template>
<style>
.ehfo_abad {
  fill: currentColor;
  d: path("M18 10h-5.17l2 2H18zM1.04 3.87l1.2 1.2C2.09 5.35 2 5.66 2 6v12c0 1.1.9 2 2 2h13.17l2.96 2.96l1.41-1.41L2.45 2.45zM4 6.83L7.17 10H6v2h2v-1.17L11.17 14H6v2h7.17l2 2H4z");
}

.rnsluqb9w {
  fill: currentColor;
  d: path("M20 4H6.83l2 2H20v11.17l1.76 1.76c.15-.28.24-.59.24-.93V6c0-1.1-.9-2-2-2");
}

</style>
