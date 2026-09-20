<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgqbonboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:moped-outline-sharp" /></template>
<style>
.qgqbonboo {
  fill: currentColor;
  d: path("M5.423 17.27q-.73-.728-.73-1.77h-2v-6h7v5h4.23l3.77-4.658v-3.15h-3v-1h4v4.466L14.46 15.5H9.693q0 1.039-.728 1.77t-1.77.73t-1.771-.73m2.828-.711q.441-.442.441-1.059h-3q0 .617.442 1.059q.441.441 1.058.441t1.059-.441m-2.56-8.867v-1h4v1zm11.347 9.58q-.731-.729-.731-1.77t.728-1.771t1.77-.731t1.771.729t.73 1.769t-.728 1.771T18.81 18t-1.771-.728m2.827-.713q.442-.442.442-1.059t-.442-1.059T18.808 14t-1.059.441q-.441.442-.441 1.059t.441 1.059q.442.441 1.059.441t1.058-.441M3.692 14.5h5v-4h-5z");
}

</style>
