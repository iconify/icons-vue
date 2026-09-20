<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6suhn5sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-wifi-4-bar-outline-rounded" /></template>
<style>
.u6suhn5sk {
  fill: currentColor;
  d: path("m10.575 19.575l-9.05-9.05q-.3-.3-.45-.675t-.15-.75q0-.425.175-.812t.525-.688Q3.675 5.825 6.5 4.913T12 4t5.5.913T22.375 7.6q.35.3.525.688t.175.812q0 .375-.15.75t-.45.675l-9.05 9.05q-.3.3-.675.45t-.75.15t-.75-.15t-.675-.45");
}

</style>
