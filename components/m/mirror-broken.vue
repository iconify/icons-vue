<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="osuf_jq5d"/><path class="e85a4hbua"/><path class="q91-j3b0a"/><path class="q1cgl7rzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-broken" /></template>
<style>
.e85a4hbua {
  d: path("M6.34141 7C6.12031 7.78195 6 8.62341 6 9.5C6 13.6421 8.68629 17 12 17C15.3137 17 18 13.6421 18 9.5C18 5.35786 15.3137 2 12 2C10.9091 2 9.88613 2.36394 9.00466 3");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.osuf_jq5d {
  d: path("M5 9.5V19C5 19.6491 4.78947 20.2807 4.4 20.8L3.5 22M19 9.5V19C19 19.6491 19.2105 20.2807 19.6 20.8L20.5 22");
}

.q1cgl7rzl {
  d: path("M13 5.25604C13.9608 5.76546 14.697 6.98826 14.9257 8.50018");
}

.q91-j3b0a {
  d: path("M5 20H12M16 20H19");
}

</style>
