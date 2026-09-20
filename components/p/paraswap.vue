<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfum1ktx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:paraswap" /></template>
<style>
.mjfum1ktx {
  fill: var(--svg-color--2669f5, #2669F5);
  d: path("M22 20L12.75 4L3.5 20zM6.25 11.5L10.5 4H2zm11.972 6.382H7.278l5.472-9.466z");
}

</style>
