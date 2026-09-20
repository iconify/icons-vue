<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n3snn_s6u"/><path class="usl_5bbok"/><path class="nxeuws7us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:red-triangle-pointed-down" /></template>
<style>
.n3snn_s6u {
  fill: var(--svg-color--c33, #c33);
  d: path("m61.32 90l-28-48.5a3.68 3.68 0 0 1 3.3-5.4h56c2.03-.03 3.7 1.6 3.73 3.63c.01.62-.14 1.22-.43 1.77l-28 48.5a3.64 3.64 0 0 1-4.84 1.76c-.78-.35-1.4-.98-1.76-1.76");
}

.nxeuws7us {
  fill: var(--svg-color--ff8a80, #ff8a80);
  d: path("M44.6 43.58c1.02 1.14 18.79 30.98 18.79 30.98s1.52 2.29-.25 3.68c-1.78 1.4-3.43 0-4.19-1.14S42.06 49.17 41.43 47.9a4.45 4.45 0 0 1 .63-4.32c.89-.89 1.91-.89 2.54 0");
}

.usl_5bbok {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M58.59 85.3L33.09 41a3.378 3.378 0 0 1 3-4.9h51a3.35 3.35 0 0 1 3.37 3.35c0 .54-.13 1.07-.37 1.55l-25.4 44.3a3.418 3.418 0 0 1-6.1 0");
}

</style>
