<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izx8o45_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:organic-badge" /></template>
<style>
.izx8o45_z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.654 8.037q.896 2.288-.576 3.963q1.472 1.675.576 3.963q-.906 2.316-3.167 2.524q-.208 2.261-2.524 3.167q-2.288.896-3.963-.576q-1.675 1.472-3.963.576q-2.316-.906-2.524-3.167q-2.261-.208-3.167-2.524q-.896-2.288.576-3.963q-1.472-1.675-.576-3.963q.906-2.316 3.167-2.524q.208-2.261 2.524-3.167q2.288-.896 3.963.576q1.675-1.472 3.963-.576q2.316.906 2.524 3.167q2.261.208 3.167 2.524M7.75 15.5q0 .149.057.287t.163.243l.007.007q.105.103.24.158q.136.055.283.055h.002q7.748-.001 7.748-7.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-7.75 0-7.75 7.75");
}

</style>
