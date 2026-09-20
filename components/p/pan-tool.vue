<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1op0-0lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pan-tool" /></template>
<style>
.u1op0-0lt {
  fill: currentColor;
  d: path("M10.05 23q-.75 0-1.4-.337T7.575 21.7L1.2 12.375l.6-.575q.475-.475 1.125-.55t1.175.3L7 13.575V4q0-.425.288-.712T8 3t.713.288T9 4v8h2V2q0-.425.288-.712T12 1t.713.288T13 2v10h2V3q0-.425.288-.712T16 2t.713.288T17 3v9h2V5q0-.425.288-.712T20 4t.713.288T21 5v14q0 1.65-1.175 2.825T17 23z");
}

</style>
