<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxd4kobaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:repeat-one-on-outline" /></template>
<style>
.nxd4kobaf {
  fill: currentColor;
  d: path("M3 22q-.413 0-.706-.294T2 21V3q0-.413.294-.706T3 2h18q.413 0 .706.294T22 3v18q0 .413-.294.706T21 22zm4.308-1l.708-.72l-2.089-2.088h12.38v-5h-1v4H5.928l2.089-2.088l-.708-.72L4 17.693zM5.692 10.808h1v-4h11.381l-2.089 2.088l.708.72L20 6.307L16.692 3l-.707.72l2.088 2.088H5.693zm6.116 3.884h.884V9.308h-2.076v.884h1.192z");
}

</style>
