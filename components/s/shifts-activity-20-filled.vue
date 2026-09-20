<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ouxo-rb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shifts-activity-20-filled" /></template>
<style>
.ouxo-rb9l {
  fill: currentColor;
  d: path("M9.997 2.707a.75.75 0 0 1-.67.822a6.506 6.506 0 1 0 7.144 7.145a.75.75 0 1 1 1.492.153a8.006 8.006 0 1 1-8.788-8.79a.75.75 0 0 1 .822.67m1.02-.066a.75.75 0 0 1 .905-.555q.568.136 1.103.35a.75.75 0 0 1-.555 1.393q-.435-.173-.898-.284a.75.75 0 0 1-.554-.904m6.547 4.333a.75.75 0 0 0-1.394.555q.173.436.285.898a.75.75 0 1 0 1.459-.35a8 8 0 0 0-.35-1.103M14.29 3.926a.75.75 0 0 1 1.058-.073q.461.401.858.867a.75.75 0 0 1-1.143.972a7 7 0 0 0-.7-.708a.75.75 0 0 1-.073-1.058M10 5.75a.75.75 0 0 0-1.5 0v5c0 .415.336.75.75.75h3a.75.75 0 1 0 0-1.5H10z");
}

</style>
