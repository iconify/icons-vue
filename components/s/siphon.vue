<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zlikhnb7c"/><path class="xo8pw1bod"/><path class="osp-9gb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:siphon" /></template>
<style>
.osp-9gb9h {
  d: path("M128 256h128V128H128v128z");
  fill: var(--svg-color--5884a3, #5884A3);
}

.xo8pw1bod {
  d: path("M128 129h128V0H128v129z");
  fill: var(--svg-color--6296ba, #6296BA);
}

.zlikhnb7c {
  d: path("M0 256h129V128H0v128z");
  fill: var(--svg-color--4c728c, #4C728C);
}

</style>
