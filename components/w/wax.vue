<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on-jltbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wax" /></template>
<style>
.on-jltbfo {
  fill: var(--svg-color--f78e1e, #f78e1e);
  d: path("m19.238 10.125l-.863.739l.881.761l1.744-1.5zM13.875 9l3.337 2.981l-1.274.769l-2.25-2.625h-1.5L8.25 15h1.5l3.188-3.75l.997 1.125H12.75l-.75.75h2.498l.69.75h1.5l1.5-1.125l1.312 1.125H21L15.375 9zM9 10.125l-.75 2.25l-.75-2.25H6l-.75 2.25l-.75-2.25H3l1.5 3.75H6l.75-2.25l.75 2.25H9l1.5-3.75z");
}

</style>
