<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="ilhq-3pfr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:treeb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ilhq-3pfr {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.65 10.61c.498-1.003.766-2.281.197-3.585c-1.222-2.815-4.041-2.767-5.939-2.448L4 5.919l2.443 13.653l5.61-.98l-.792-4.079l.247-.068l2.35 3.805L20 17.086l-3.555-4.799a3.7 3.7 0 0 1-1.041.55l-4.032.797c-1.463.357-4.103-.676-4.103-3.249c0-2.578 1.79-3.582 2.689-3.766l3.65-.628c.975-.164 3.292-.048 3.968 2.115c.309.985.29 1.818.073 2.503m-.103-1.138c0 1.854-1.516 3.36-3.38 3.36a3.365 3.365 0 0 1-3.119-2.07a3.4 3.4 0 0 1-.26-1.29c0-1.854 1.511-3.355 3.38-3.355a3.37 3.37 0 0 1 3.38 3.355");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
