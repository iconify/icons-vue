<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l55_bib6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-find-outline" /></template>
<style>
.l55_bib6a {
  fill: currentColor;
  d: path("M12 21L0 8.975q2.325-2.325 5.388-3.65T12 4t6.613 1.325T24 8.975L22.6 10.4q-2.025-2.025-4.75-3.213T12 6q-2.575 0-4.875.813t-4.2 2.262l10.475 10.5zm9.6-1l-2.575-2.55q-.45.275-.95.413T17 18q-1.7 0-2.85-1.15T13 14t1.15-2.85T17 10t2.85 1.15T21 14q0 .575-.137 1.075t-.413.95L23 18.6zm-3.175-4.575Q19 14.85 19 14t-.575-1.425T17 12t-1.425.575T15 14t.575 1.425T17 16t1.425-.575M12 19.575");
}

</style>
