<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3-ibom1w"/><path class="jzkoojbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-smart-screen" /></template>
<style>
.e3-ibom1w {
  fill: currentColor;
  d: path("M3 17h1V7H3zM20 7v10h1V7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.jzkoojbyb {
  fill: currentColor;
  d: path("M14 11.25h-1.5v1.5H14zm2.5 0H15v1.5h1.5zm-5 0H10v1.5h1.5zm-2.5 0H7.5v1.5H9zM21 5H3c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2M4 17H3V7h1zm14 0H6V7h12zm3 0h-1V7h1z");
}

</style>
