<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lemrodbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:moped-package-outline" /></template>
<style>
.lemrodbma {
  fill: currentColor;
  d: path("M4 8.116V4h5.692v4.116zm1-1h3.692V5H5zm.423 10.155q-.73-.73-.73-1.771h-2V13q0-1.458 1.02-2.479T6.194 9.5h3.5v5h4.23l3.77-4.658V7.308q0-.27-.174-.442q-.173-.174-.442-.174h-2.385v-1h2.385q.666 0 1.14.475t.475 1.14v2.85l-4.23 5.343h-4.77q0 1.039-.728 1.77t-1.77.73t-1.771-.73m2.828-.711q.441-.442.441-1.059h-3q0 .617.442 1.059q.441.441 1.058.441t1.059-.441m8.788.712q-.731-.728-.731-1.769t.728-1.771t1.77-.731t1.771.729t.73 1.769t-.728 1.771t-1.77.731t-1.771-.728m2.827-.713q.442-.442.442-1.059t-.442-1.059T18.808 14t-1.059.441q-.441.442-.441 1.059t.441 1.059q.442.441 1.059.441t1.058-.441M3.692 14.5h5v-4H6.19q-1.033 0-1.765.735q-.732.734-.732 1.765zm5-7.384V5zm0 7.384");
}

</style>
