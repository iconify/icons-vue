<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi2b62baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop-rotate" /></template>
<style>
.oi2b62baj {
  fill: currentColor;
  d: path("M7.47 21.49C4.2 19.93 1.86 16.76 1.5 13H0c.51 6.16 5.66 11 11.95 11c.23 0 .44-.02.66-.03L8.8 20.15zM12.05 0c-.23 0-.44.02-.66.04l3.81 3.81l1.33-1.33C19.8 4.07 22.14 7.24 22.5 11H24c-.51-6.16-5.66-11-11.95-11M16 14h2V6h-8v2h6zm-8 2V4H6v2H4v2h2v10h10v2h2v-2h2v-2z");
}

</style>
