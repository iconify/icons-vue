<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpgzkwb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mouse-vertical" /></template>
<style>
.qpgzkwb2d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.516 2.567q2.127.453 3.311 2.276q1.185 1.824.733 3.951l-1.871 8.803q-.453 2.127-2.276 3.311q-1.824 1.185-3.951.733t-3.311-2.276q-.656-1.01-.81-2.113q-.521.498-1.341.498q-2.25 0-2.25-3.75T5 10.25q1.647 0 2.089 2.011l1.2-5.65q.453-2.127 2.276-3.311q1.824-1.185 3.951-.733m-.149 4.313q.015-.072.016-.146t-.013-.147q-.013-.072-.04-.141t-.068-.13q-.04-.062-.092-.115q-.051-.053-.112-.095t-.129-.071t-.14-.045q-.072-.015-.146-.016t-.147.013q-.072.013-.141.04t-.13.068t-.115.092t-.095.112t-.071.129t-.045.14l-.624 2.935q-.015.072-.016.146t.013.147t.04.141t.068.13q.04.062.092.115q.051.053.112.095t.129.071t.14.045t.146.016t.147-.013q.072-.013.141-.04t.13-.068q.062-.04.115-.092q.053-.051.095-.112t.071-.129t.045-.14z");
}

</style>
