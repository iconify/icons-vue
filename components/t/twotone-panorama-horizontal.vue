<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrzx16q5z"/><path class="ru5gq-jfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-panorama-horizontal" /></template>
<style>
.rrzx16q5z {
  fill: currentColor;
  d: path("M4 6.54v10.91c2.6-.77 5.28-1.16 8-1.16s5.4.39 8 1.16V6.54c-2.6.78-5.28 1.17-8 1.16c-2.72 0-5.4-.39-8-1.16");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ru5gq-jfz {
  fill: currentColor;
  d: path("M21.43 4c-.1 0-.2.02-.31.06C18.18 5.16 15.09 5.7 12 5.7s-6.18-.55-9.12-1.64A1 1 0 0 0 2.57 4c-.34 0-.57.23-.57.63v14.75c0 .39.23.62.57.62c.1 0 .2-.02.31-.06c2.94-1.1 6.03-1.64 9.12-1.64s6.18.55 9.12 1.64c.11.04.21.06.31.06c.33 0 .57-.23.57-.63V4.63c0-.4-.24-.63-.57-.63M20 17.45c-2.6-.77-5.28-1.16-8-1.16s-5.4.39-8 1.16V6.54c2.6.77 5.28 1.16 8 1.16c2.72.01 5.4-.38 8-1.16z");
}

</style>
