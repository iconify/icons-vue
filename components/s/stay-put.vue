<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzo15fbud"/><path class="nmqmx4bsn"/><path class="nwv4bhb9w"/><path class="golxjybxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stay-put" /></template>
<style>
.golxjybxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.495 27.4c2.029 1.183 1.061 3.698.308 6.118");
}

.mzo15fbud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.587 28.614c3.685 1.583 5.568 4.107 7.646 6.53c-.42 11.844 16.307 8.975 15.483 4.298");
}

.nmqmx4bsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.45 24.016c8.65 11.178-4.328 24.54-16.217 12.041");
}

.nwv4bhb9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.896 26.266c-.302-6.072 4.864-12.648 1.553-16.842c-1.526-1.718-3.052-.81-3.161 2.758c-.132 4.332-1.997 9.803-3.539 9.562S30.378 4.569 26.718 4.5s-1.643 10.013-1.58 17.56c-1.49-6.525-5.94-16.713-9.143-14.694c-1.537.969.999 8.758 2.557 12.57c1.346 3.29 1.682 6.197 1.687 9.086c-6.642-8.218-11.036-6.687-11.537-5.55c-1.03 2.34 1.18 4.133 2.884 5.142");
}

</style>
