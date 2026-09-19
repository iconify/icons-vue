<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0t8hd3qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-near-me" /></template>
<style>
.g0t8hd3qy {
  fill: currentColor;
  d: path("m17.27 6.73l-4.24 10.13l-1.32-3.42l-.32-.83l-.82-.32l-3.43-1.33zM21 3L3 10.53v.98l6.84 2.65L12.48 21h.98z");
}

</style>
