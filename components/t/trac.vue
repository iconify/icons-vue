<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGRAe6Yacu)" class="hp08i6-8m"/><defs><linearGradient id="SVGRAe6Yacu" x1="4.861" x2="19.245" y1="7.111" y2="16.249" gradientUnits="userSpaceOnUse"><stop class="sqmwf1uff"/><stop offset="1" class="h2vaqubkn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trac" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h2vaqubkn {
  stop-color: var(--svg-color--30c7b4, #30c7b4);
}

.hp08i6-8m {
  d: path("M12 3v4.477a4.522 4.522 0 1 0 3.46 7.437l3.425 2.88A8.96 8.96 0 0 1 12 21a9 9 0 0 1 0-18m4.247 10.564l4.202 1.552c-.186.49-.405.962-.675 1.418l-3.865-2.256q.2-.343.338-.714m4.612-3.128q.142.762.141 1.564h-4.478c0-.27-.022-.529-.067-.788l4.41-.776zm-3.048-5.304c.404.337.77.709 1.108 1.114l-3.443 2.863a4.6 4.6 0 0 0-.551-.563z");
}

.sqmwf1uff {
  stop-color: var(--svg-color--4ccb88, #4ccb88);
}

</style>
