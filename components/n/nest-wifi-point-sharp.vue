<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqgxdqb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-wifi-point-sharp" /></template>
<style>
.eqgxdqb5q {
  fill: currentColor;
  d: path("M8.73 20q-1.97 0-3.35-1.38T4 15.27V8.73q0-1.97 1.38-3.35T8.73 4h6.54q1.97 0 3.35 1.38T20 8.73v6.54q0 1.97-1.38 3.35T15.27 20zm.347-1q0-.367.24-.607q.239-.24.606-.24q.368 0 .607.244q.24.244.24.603h2.46q0-.367.24-.607t.607-.24t.607.244t.239.603q1.356 0 2.14-.434q.785-.435 1.31-1.258H17q0 .36-.24.602q-.239.244-.606.244q-.368 0-.607-.244q-.24-.243-.24-.602h-2.46q0 .367-.24.606q-.24.24-.607.24t-.607-.244t-.24-.602h-2.46q0 .367-.24.606q-.24.24-.607.24t-.607-.244Q7 17.668 7 17.309H5.627q.525.823 1.31 1.257q.784.435 2.14.435");
}

</style>
