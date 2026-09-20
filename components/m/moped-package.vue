<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5duslbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:moped-package" /></template>
<style>
.v5duslbyw {
  fill: currentColor;
  d: path("M4 8.116V4h5.692v4.116zm1.423 9.153q-.73-.73-.73-1.769h-2V13q0-1.458 1.02-2.479T6.194 9.5h3.5v5h4.23l3.77-4.658V7.308q0-.27-.174-.442q-.173-.174-.442-.174h-2.385v-1h2.385q.671 0 1.143.473q.472.472.472 1.143v2.85l-4.23 5.342h-4.77q0 1.039-.73 1.77t-1.77.73t-1.769-.73m2.828-.711q.441-.442.441-1.059h-3q0 .617.442 1.059q.441.441 1.058.441t1.059-.441m8.788.71q-.731-.73-.731-1.769t.73-1.77t1.77-.73t1.769.73t.73 1.77t-.73 1.77t-1.77.73t-1.768-.73m2.827-.711q.442-.442.442-1.059t-.442-1.059T18.808 14t-1.059.441q-.441.442-.441 1.059t.441 1.059q.442.441 1.059.441t1.058-.441");
}

</style>
