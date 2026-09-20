<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quj__2p6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-farsight-seasonal-rounded" /></template>
<style>
.quj__2p6h {
  fill: currentColor;
  d: path("M12 7.125q-.45-.325-.962-.475T10 6.5q-.675 0-1.325.263t-1.15.762t-.763 1.15T6.5 10q0 .525.15 1.038t.475.962q-.325.45-.475.963T6.5 14q0 .675.263 1.325t.762 1.15t1.15.762T10 17.5q.525 0 1.038-.15t.962-.475q.45.325.963.475T14 17.5q.675 0 1.325-.263t1.15-.762t.762-1.15T17.5 14q0-.525-.15-1.038T16.875 12q.325-.45.475-.962T17.5 10q0-.675-.262-1.325t-.763-1.15t-1.15-.763T14 6.5q-.525 0-1.037.15T12 7.125m.888 5.763q.362-.363.362-.888t-.363-.888T12 10.75t-.888.363t-.362.887t.363.888t.887.362t.888-.363M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
