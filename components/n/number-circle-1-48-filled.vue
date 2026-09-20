<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qe7fa_b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-1-48-filled" /></template>
<style>
.qe7fa_b5y {
  fill: currentColor;
  d: path("M24 44c11.046 0 20-8.954 20-20S35.046 4 24 4S4 12.954 4 24s8.954 20 20 20m2.5-29.75v18.5a1.25 1.25 0 1 1-2.5 0V19.672c-1.006 1.297-2.406 2.546-4.318 3.25a1.25 1.25 0 1 1-.864-2.345c1.98-.73 3.286-2.315 4.117-3.833c.41-.75.687-1.454.861-1.968a10 10 0 0 0 .224-.755l.008-.034v-.004l.001-.001a1.25 1.25 0 0 1 2.471.268");
}

</style>
