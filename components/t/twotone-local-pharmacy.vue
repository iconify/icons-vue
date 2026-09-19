<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srdibradz"/><path class="or5c_ybsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-pharmacy" /></template>
<style>
.or5c_ybsv {
  fill: currentColor;
  d: path("M3 21h18v-2l-2-6l2-6V5h-2.64l1.14-3.14L17.15 1l-1.46 4H3v2l2 6l-2 6zm3.9-8.63L5.11 7h13.78l-1.79 5.37l-.21.63l.21.63L18.89 19H5.11l1.79-5.37l.21-.63zM11 17h2v-3h3v-2h-3V9h-2v3H8v2h3z");
}

.srdibradz {
  fill: currentColor;
  d: path("M5.11 19h13.78l-1.79-5.37l-.21-.63l.21-.63L18.89 7H5.11l1.79 5.37l.21.63l-.21.63zM8 12h3V9h2v3h3v2h-3v3h-2v-3H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
