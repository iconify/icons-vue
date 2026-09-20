<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3bvc3bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pi-24-filled" /></template>
<style>
.j3bvc3bhw {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3-3h15.25a1 1 0 1 1 0 2H17v10.703a1.5 1.5 0 0 0 2.005 1.412l.159-.057a1 1 0 1 1 .672 1.884l-.159.057c-2.28.814-4.677-.876-4.677-3.296V6H9.979a68 68 0 0 1-.36 4.21c-.316 2.683-.89 6.142-1.924 9.118a1 1 0 1 1-1.89-.656c.965-2.774 1.518-6.065 1.827-8.695A66 66 0 0 0 7.976 6H5a1 1 0 0 0-1 1v.5a1 1 0 0 1-2 0z");
}

</style>
