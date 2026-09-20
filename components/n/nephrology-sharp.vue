<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsycs39-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nephrology-sharp" /></template>
<style>
.xsycs39-u {
  fill: currentColor;
  d: path("M9 21v-4.175q-.25.1-.488.138T8 17q-2.5 0-4.25-1.75T2 11V9q0-2.5 1.75-4.25T8 3q1.25 0 2.125.875T11 6t-.875 2.125T8 9v2q1.25 0 2.125.875T11 14v7zm4 0v-7q0-1.25.875-2.125T16 11V9q-1.25 0-2.125-.875T13 6t.875-2.125T16 3q2.5 0 4.25 1.75T22 9v2q0 2.5-1.75 4.25T16 17q-.275 0-.513-.038T15 16.825V21z");
}

</style>
