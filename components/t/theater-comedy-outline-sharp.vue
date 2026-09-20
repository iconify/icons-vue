<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u98mmz8pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:theater-comedy-outline-sharp" /></template>
<style>
.u98mmz8pz {
  fill: currentColor;
  d: path("M18.5 7.308q.329 0 .568-.24t.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24m-4 0q.329 0 .568-.24t.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24m-.27 3.4h4.54q-.097-.664-.754-1.09T16.5 9.192q-.898 0-1.555.426t-.714 1.09M3.96 19.542Q2.5 18.083 2.5 16v-6h10v6q0 2.083-1.457 3.542T7.505 21t-3.543-1.458m6.363-.717Q11.5 17.65 11.5 16v-5h-8v5q0 1.65 1.175 2.825T7.5 20t2.825-1.175M16.5 14q-.67 0-1.374-.185q-.705-.186-1.164-.519L14 12.1q.539.425 1.163.663T16.5 13q1.65 0 2.825-1.175T20.5 9V4h-8v4.5h-1V3h10v6q0 2.083-1.458 3.542Q18.583 14 16.5 14m-11 .308q.329 0 .568-.24t.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24m4.568-.24q.24-.24.24-.568t-.24-.568t-.568-.24t-.568.24t-.24.568t.24.568t.568.24t.568-.24m-1.013 3.214q.656-.426.714-1.09H5.231q.058.664.714 1.09t1.555.426t1.555-.426M16.5 8.5");
}

</style>
