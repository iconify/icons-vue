<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo452-80r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-phone-disabled" /></template>
<style>
.mo452-80r {
  fill: currentColor;
  d: path("M14.52 17.35C11.39 19.83 7.36 21.22 3 20.97v-5.51l5.27-.61l2.52 2.52c.81-.41 1.58-.9 2.3-1.45L1.39 4.22l1.42-1.41L21.19 21.2l-1.41 1.41zm1.39-4.24c.56-.73 1.05-1.51 1.47-2.33l-2.53-2.53l.61-5.25h5.51c.25 4.37-1.15 8.4-3.63 11.54z");
}

</style>
