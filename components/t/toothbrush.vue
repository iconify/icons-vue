<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="l3w_f4b4q"/><path class="tsjt6t1zw"/><path class="jg9lkp76o"/><path class="n85zp3bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:toothbrush" /></template>
<style>
.jg9lkp76o {
  fill: var(--svg-color--289193, #289193);
  d: path("M31.996 34.325a2.005 2.005 0 0 1-2.828 0L11.49 16.648a2.005 2.005 0 0 1 0-2.828a2.005 2.005 0 0 1 2.828 0l17.678 17.678c.778.777.778 2.05 0 2.827");
}

.l3w_f4b4q {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m5.833 6.748l5.657-5.657l.707 2.122l2.122.707l.707 2.121l2.121.707l.707 2.121l2.121.708l-5.656 5.656z");
}

.n85zp3bhk {
  fill: var(--svg-color--3db8c1, #3db8c1);
  d: path("M15.026 17.355a2.005 2.005 0 0 1-2.828 0L3.712 8.869a1.003 1.003 0 0 1 0-1.414l1.414-1.414a1.003 1.003 0 0 1 1.414 0l8.485 8.485c.779.778.779 2.051.001 2.829");
}

.tsjt6t1zw {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M11.844 4.273L7.248 8.869a.5.5 0 0 1-.707-.707l4.596-4.596a.5.5 0 0 1 .707.707m1.414 1.415l-4.596 4.596a.5.5 0 0 1-.707-.707l4.596-4.596a.5.5 0 0 1 .707.707m1.414 1.414l-4.596 4.596a.5.5 0 0 1-.707-.707l4.596-4.596a.5.5 0 0 1 .707.707m1.414 1.414l-4.596 4.596a.5.5 0 0 1-.707-.707l4.596-4.596a.5.5 0 0 1 .707.707m1.415 1.414l-4.596 4.596a.5.5 0 0 1-.707-.707l4.596-4.596a.5.5 0 0 1 .707.707");
}

</style>
