<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-okebcfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sequence-reply-stop" /></template>
<style>
.j-okebcfs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 6q0-3.25 3.25-3.25h11q3.25 0 3.25 3.25v7.626q-.474-.126-1-.126h-2.5q-3.75 0-3.75 3.75h-2.218l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.755q-3-.123-3-3.245zm14 8.75h2.5q1.036 0 1.768.732t.732 1.768v2.5q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732t-.732-1.768v-2.5q0-2.5 2.5-2.5m0 1.5q-1 0-1 1v2.5q0 .414.293.707t.707.293h2.5q.414 0 .707-.293t.293-.707v-2.5q0-1-1-1z");
}

</style>
