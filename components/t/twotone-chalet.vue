<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzhf2g_bz"/><path class="attd3zbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-chalet" /></template>
<style>
.attd3zbbd {
  fill: currentColor;
  d: path("M17.5 15L10 7.5L2.5 15l1.41 1.41L5 15.33V20h10v-4.67l1.09 1.09zM13 18h-2v-3H9v3H7v-4.67l3-3l3 3zm9-10.5h-1.19l.75.75l-.71.71l-1.46-1.46h-.89v.89l1.45 1.45l-.71.71l-.74-.74V11h-1V9.81l-.75.75l-.71-.71l1.45-1.45v-.9h-.89l-1.45 1.45l-.71-.71l.75-.75H14v-1h1.19l-.75-.75l.71-.71l1.45 1.45h.89v-.87l-1.45-1.45l.71-.71l.75.75V3h1v1.19l.75-.75l.71.71l-1.46 1.46v.89h.89l1.45-1.45l.71.71l-.74.74H22z");
}

.hzhf2g_bz {
  fill: currentColor;
  d: path("M13 18h-2v-3H9v3H7v-4.67l3-3l3 3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
