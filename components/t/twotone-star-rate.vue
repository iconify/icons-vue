<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdl-abw2c"/><path class="fazbtmbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-star-rate" /></template>
<style>
.fazbtmbtq {
  fill: currentColor;
  d: path("M22 10h-7.58L12 2l-2.42 8H2l6.17 4.41L5.83 22L12 17.31L18.17 22l-2.35-7.59zm-7.58 6.63L12 14.79l-2.42 1.84l.93-3.01L8.24 12h2.82L12 8.89l.94 3.11h2.82l-2.27 1.62z");
}

.fdl-abw2c {
  fill: currentColor;
  d: path("M12.94 12L12 8.89L11.06 12H8.24l2.27 1.62l-.93 3.01L12 14.79l2.42 1.84l-.93-3.01L15.76 12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
