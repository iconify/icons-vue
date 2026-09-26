<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfv91usyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevron-left-sharp-fill" /></template>
<style>
.lfv91usyq {
  fill: currentColor;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM13.5858 7L9.2929 11.2929C8.9024 11.6834 8.9024 12.3166 9.2929 12.7071L13.5858 17L15 15.5858L11.4142 12L15 8.4142L13.5858 7Z");
}

</style>
