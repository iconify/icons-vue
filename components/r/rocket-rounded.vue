<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdbfeqbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rocket-rounded" /></template>
<style>
.sdbfeqbhp {
  fill: currentColor;
  d: path("M6.625 20.142q-.404.162-.755-.08t-.35-.671V15.46q0-.404.189-.768q.189-.363.537-.58l1.196-.783q.175 1.736.451 3.019t.909 2.927zm3.56-1.334q-.293 0-.485-.196t-.298-.464q-.54-1.532-.818-2.832q-.276-1.299-.276-2.93q0-2.434.75-4.49t2.36-3.729q.11-.13.266-.183q.155-.053.316-.053t.316.053t.267.183q1.61 1.672 2.36 3.728t.75 4.492q0 1.655-.268 2.932t-.827 2.829q-.106.268-.298.464t-.484.196zm2.881-6.742q.434-.433.434-1.066t-.434-1.066T12 9.5t-1.066.434T10.5 11t.434 1.066T12 12.5t1.066-.434m4.29 8.095l-2.177-.867q.633-1.644.909-2.936t.45-3.03l1.197.803q.348.217.537.58q.19.364.19.768v3.93q0 .43-.351.672t-.755.08");
}

</style>
