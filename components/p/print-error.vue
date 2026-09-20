<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj8lg7fuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:print-error" /></template>
<style>
.uj8lg7fuj {
  fill: currentColor;
  d: path("M6 21v-4H2v-6q0-1.275.875-2.137T5 8h14q1 0 1.763.563T21.825 10H18q-.825 0-1.412.588T16 12v3H8v4h8v2zM6 7V3h12v4zm12.288 13.713Q18 20.425 18 20t.288-.712T19 19t.713.288T20 20t-.288.713T19 21t-.712-.288M18 17v-5h2v5z");
}

</style>
