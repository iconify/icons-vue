<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmdpcubuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:variable-add-sharp" /></template>
<style>
.pmdpcubuu {
  fill: currentColor;
  d: path("M3 17V7h18v3.075q-.25-.05-.488-.062T20 10q-2.5 0-4.25 1.75T14 16q0 .275.013.513t.062.487zm16 3v-3h-3v-2h3v-3h2v3h3v2h-3v3z");
}

</style>
