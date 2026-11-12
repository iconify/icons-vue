<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="gglewhb8d"/><path class="qnqkq7bki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:toggle-right-outline" /></template>
<style>
.gglewhb8d {
  d: path("M16 8.25C18.0711 8.25 19.75 9.92889 19.75 12C19.75 14.0711 18.0711 15.75 16 15.75C13.9289 15.75 12.25 14.0711 12.25 12C12.25 9.92889 13.9289 8.25 16 8.25ZM16 9.75C14.7573 9.75 13.75 10.7573 13.75 12C13.75 13.2427 14.7573 14.25 16 14.25C17.2427 14.25 18.25 13.2427 18.25 12C18.25 10.7573 17.2427 9.75 16 9.75Z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.qnqkq7bki {
  d: path("M16 5.25C19.7279 5.25 22.75 8.27209 22.75 12C22.75 15.7279 19.7279 18.75 16 18.75H8C4.27209 18.75 1.25 15.7279 1.25 12C1.25 8.27209 4.27209 5.25 8 5.25H16ZM8 6.75C5.10051 6.75 2.75 9.10051 2.75 12C2.75 14.8995 5.10051 17.25 8 17.25H16C18.8995 17.25 21.25 14.8995 21.25 12C21.25 9.10051 18.8995 6.75 16 6.75H8Z");
}

</style>
