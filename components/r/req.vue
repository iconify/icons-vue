<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jdd29p4_g"/><path class="ot7qhq_xv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:req" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jdd29p4_g {
  fill: var(--svg-color--69e2a5, #69e2a5);
  d: path("M6.211 3A2.37 2.37 0 0 0 3.84 5.371V18.9a2.1 2.1 0 1 0 4.2 0V6.6h8.4l3.6-3.6z");
}

.ot7qhq_xv {
  fill: var(--svg-color--3d8a65, #3d8a65);
  d: path("M20.04 8.304v-5.29l-9.094 8.977a1.65 1.65 0 0 0-.014 2.337l5.958 6.031a1.91 1.91 0 1 0 2.721-2.68l-4.102-4.177a.493.493 0 0 1 .003-.695z");
}

</style>
