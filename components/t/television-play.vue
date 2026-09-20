<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="s21a4zb2x"/><path class="pydu1nxom"/><path class="symo1x26t"/><path class="ej65a380j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:television-play" /></template>
<style>
.ej65a380j {
  d: path("M12.5 11.5a.5.5 0 0 1-.238.426l-3.25 2a.5.5 0 0 1-.762-.426v-4a.5.5 0 0 1 .762-.426l3.25 2a.5.5 0 0 1 .238.426m-3.25-1.105v2.21l1.796-1.105z");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.pydu1nxom {
  d: path("M9.875 5.78a1 1 0 0 1-.156-1.405l2-2.5a1 1 0 0 1 1.562 1.25l-2 2.5a1 1 0 0 1-1.406.156");
}

.s21a4zb2x {
  d: path("M4 8v7a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1m-2 7a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3H5a3 3 0 0 0-3 3z");
}

.symo1x26t {
  d: path("M10.125 5.78a1 1 0 0 0 .156-1.405l-2-2.5a1 1 0 1 0-1.562 1.25l2 2.5a1 1 0 0 0 1.406.156M12 11.5l-3.25 2v-4z");
}

</style>
