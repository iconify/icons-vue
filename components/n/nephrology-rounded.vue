<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp_jgpn5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nephrology-rounded" /></template>
<style>
.fp_jgpn5i {
  fill: currentColor;
  d: path("M8 17q-2.5 0-4.25-1.75T2 11V9q0-2.5 1.75-4.25T8 3q1.25 0 2.125.875T11 6t-.875 2.125T8 9v2q1.25 0 2.125.875T11 14v6q0 .425-.288.713T10 21t-.712-.288T9 20v-3.175q-.25.1-.488.138T8 17m8 0q-.275 0-.513-.038T15 16.825V20q0 .425-.288.713T14 21t-.712-.288T13 20v-6q0-1.25.875-2.125T16 11V9q-1.25 0-2.125-.875T13 6t.875-2.125T16 3q2.5 0 4.25 1.75T22 9v2q0 2.5-1.75 4.25T16 17");
}

</style>
