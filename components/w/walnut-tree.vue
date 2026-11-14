<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4t_kmb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:walnut-tree" /></template>
<style>
.l4t_kmb_h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.98 13.998Q3.943 16.75 7 16.75h4.25v4.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4.75H15q3.817 0 5.077-2.239q1.948-1.427 1.638-4.523q-.304-3.041-2.552-4.035q-.579-2.625-3.413-3.629q-2.72-.963-4.884.367q-2.901-.663-5.321 1.641Q3.09 6.67 3.683 9.778q-1.547 1.808-.703 4.22M9 10q0-1.45 1.025-2.476Q11.05 6.499 12.5 6.499t2.475 1.025Q16.001 8.55 16 10q.001 1.45-1.025 2.476q-1.025 1.025-2.475 1.025t-2.475-1.025T9 10");
}

</style>
