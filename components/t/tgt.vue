<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGDLyrNbtQ)" class="fazy38jtp"/><defs><linearGradient id="SVGDLyrNbtQ" x1="3.281" x2="20.719" y1="21" y2="21" gradientUnits="userSpaceOnUse"><stop class="a1zkku_qb"/><stop offset="1" class="s6e45k5td"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tgt" /></template>
<style>
.a1zkku_qb {
  stop-color: var(--svg-color--0cf, #0cf);
}

.fazy38jtp {
  d: path("M12.827 11.674L8.41 7.646L20.72 3zm4.421 4.033L3.281 21l9.546-9.326z");
}

.ft5dv1b6b {
  fill: none;
}

.s6e45k5td {
  stop-color: var(--svg-color--3f9, #3f9);
}

</style>
