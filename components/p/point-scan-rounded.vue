<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbeel0bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:point-scan-rounded" /></template>
<style>
.fbeel0bbq {
  fill: currentColor;
  d: path("M10.934 13.066Q10.5 12.633 10.5 12t.434-1.066T12 10.5t1.066.434q.434.433.434 1.066t-.434 1.066T12 13.5t-1.066-.434M11.5 7.5v-3q0-.213.144-.356T12.001 4t.356.144t.143.356v3q0 .213-.144.356T11.999 8t-.356-.144T11.5 7.5m0 12v-3q0-.213.144-.356t.357-.144t.356.144t.143.356v3q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356m5-8h3q.213 0 .356.144t.144.357t-.144.356t-.356.143h-3q-.213 0-.356-.144T16 11.999t.144-.356t.356-.143m-12 0h3q.213 0 .356.144t.144.357t-.144.356t-.356.143h-3q-.213 0-.356-.144T4 11.999t.144-.356t.356-.143");
}

</style>
