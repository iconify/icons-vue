<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-s66g8ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wash-40" /></template>
<style>
.r-s66g8ig {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.502 6.439q2.748-2.442 5.496 0q1.752 1.558 3.504 0q2.748-2.442 5.496 0q1.752 1.558 3.504 0q.111-.099.252-.148t.29-.04t.283.074t.234.177q.057.064.098.141q.042.076.064.159q.023.084.026.17q.004.087-.013.172l-2.25 11.5q-.012.064-.036.124t-.056.116q-.033.056-.075.105t-.092.09t-.107.073t-.117.054t-.124.033t-.129.011H5.25q-.065 0-.129-.011q-.063-.011-.124-.033t-.117-.054q-.057-.032-.107-.073t-.092-.09t-.075-.105t-.056-.116q-.024-.06-.036-.124l-2.25-11.5q-.019-.096-.012-.194q.006-.097.037-.19q.032-.092.086-.174t.127-.147M9.25 10.5q-2 0-2 2t2 2q.828 0 1.414-.586t.586-1.414t-.586-1.414T9.25 10.5m3.5 2q0 2 2 2t2-2t-2-2t-2 2");
}

</style>
