<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uekg2eekl"/><path class="pi5rlybqa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:neo" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pi5rlybqa {
  fill: var(--svg-color--00af92, #00af92);
  d: path("m19.677 17.823l-7.941-3.261V9.268l7.941-2.955z");
}

.uekg2eekl {
  fill: var(--svg-color--00e599, #00e599);
  d: path("m11.206 21l-6.883-2.859V6.23L13.498 3l6.078 2.827l-8.37 2.997z");
}

</style>
