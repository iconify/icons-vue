<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe8t51buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-0-rounded" /></template>
<style>
.fe8t51buj {
  fill: currentColor;
  d: path("m10.575 17.575l-4.15-4.15q-.3-.3-.45-.675t-.15-.75t.15-.75t.45-.675l4.15-4.15q.3-.3.675-.45t.75-.15t.75.15t.675.45l4.15 4.15q.3.3.45.675t.15.75t-.15.75t-.45.675l-4.15 4.15q-.3.3-.675.45t-.75.15t-.75-.15t-.675-.45");
}

</style>
