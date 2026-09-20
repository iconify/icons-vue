<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGTwZs9bbX)" class="ut-2mccoy"/><defs><linearGradient id="SVGTwZs9bbX" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="q29ryybcc"/><stop offset="1" class="o24ughb8g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pxp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o24ughb8g {
  stop-color: var(--svg-color--057eff, #057eff);
}

.q29ryybcc {
  stop-color: var(--svg-color--5bc5f7, #5bc5f7);
}

.ut-2mccoy {
  d: path("M13.125 3h-2.25v1.687H5.813v2.25h1.124V18.75H5.812V21h4.5v-2.25H9.187v-3.937h1.688V16.5h2.25v-1.687c2.801-.023 5.062-2.296 5.062-5.063a5.09 5.09 0 0 0-5.062-5.063zm-3.938 9.563V6.937h3.91a2.824 2.824 0 0 1 2.84 2.813c0 1.553-1.27 2.813-2.84 2.813z");
}

</style>
