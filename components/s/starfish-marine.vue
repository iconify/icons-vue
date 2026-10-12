<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zle_06fto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:starfish-marine" /></template>
<style>
.zle_06fto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.44 3.65l1.62 3.26q.44.9 1.36 1.29l4.1 1.7q.92.38.04.84l-2.63 1.36q-.89.46-.72 1.45l.62 3.59q.17.99-.72.52l-3.22-1.69q-.89-.47-1.86-.24l-4.32 1.03q-.97.24-.52-.66l1.32-2.64q.45-.9-.27-1.59L4.63 9.32q-.71-.7.28-.84l3.6-.52q.99-.15 1.43-1.05l1.62-3.26q.44-.9.88 0M12 6.5h.01m4.71 4.21h.01m-1.94 4.38h.01m-6.3-.63h.01M7.48 9.78h.01M2.75 21c2.5-.75 4.5-.75 6.5 0m5.5 0c2.5-.75 4.5-.75 6.5 0");
}

</style>
