<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-n_fsbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:solid-shapes" /></template>
<style>
.a-n_fsbpa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.872 4.956l2.197 3.296q.748 1.121.112 2.31q-.636 1.188-1.984 1.188H9.803q-1.348 0-1.984-1.188q-.636-1.189.112-2.31l2.197-3.296Q10.796 3.954 12 3.954t1.872 1.002M4.75 11.75h4.5q1.036 0 1.768.732t.732 1.768v4.5q0 1.036-.732 1.768t-1.768.732h-4.5q-2.5 0-2.5-2.5v-4.5q0-2.5 2.5-2.5m8.891 1.391Q12.25 14.532 12.25 16.5t1.391 3.359T17 21.25t3.359-1.391T21.75 16.5t-1.391-3.359T17 11.75t-3.359 1.391");
}

</style>
