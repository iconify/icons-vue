<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5-9wfb5q"/><path class="k3c_um9jf"/><path class="r0hr0xiwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-type-specimen" /></template>
<style>
.k3c_um9jf {
  fill: currentColor;
  d: path("M22 2H6v16h16zm-5.37 12.5l-.8-2.3H12.2l-.82 2.3H9.81l3.38-9h1.61l3.38 9z");
}

.q5-9wfb5q {
  fill: currentColor;
  d: path("M4 6H2v16h16v-2H4z");
}

.r0hr0xiwf {
  fill: currentColor;
  d: path("m13.96 7.17l-1.31 3.72h2.69l-1.3-3.72z");
}

</style>
