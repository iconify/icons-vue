<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxxst1_ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-panorama-wide-angle-select" /></template>
<style>
.sxxst1_ei {
  fill: currentColor;
  d: path("M12 4c-3.97 0-6.85.63-9 1c-.55 1.97-1 3.92-1 7c0 3.03.45 5.05 1 7c2.15.37 4.98 1 9 1c3.97 0 6.85-.63 9-1c.57-2.02 1-3.99 1-7c0-3.03-.45-5.05-1-7c-2.15-.37-4.98-1-9-1");
}

</style>
