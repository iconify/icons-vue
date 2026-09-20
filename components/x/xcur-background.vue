<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path clip-rule="evenodd" class="upde8acyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xcur-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.upde8acyf {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0-8 8a8 8 0 0 0 8 8m5.39-5.36c.256-.523-.096-1.107-.663-1.235c-.515-.115-1.02.192-1.292.645a3.999 3.999 0 1 1-.162-4.35c.323.459.904.73 1.424.521c.504-.203.76-.779.484-1.248A6 6 0 0 0 12 6a6 6 0 1 0 5.39 8.64");
}

</style>
