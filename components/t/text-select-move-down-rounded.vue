<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9f-gib9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-select-move-down-rounded" /></template>
<style>
.v9f-gib9q {
  fill: currentColor;
  d: path("M4.5 5q-.213 0-.356-.144T4 4.499t.144-.356T4.5 4h15q.213 0 .356.144t.144.357t-.144.356T19.5 5zm6.935 10.742l-2.389-2.388q-.14-.14-.153-.341t.157-.371q.156-.155.35-.146t.354.15l1.746 1.721V8q0-.213.144-.356t.357-.144t.356.144T12.5 8v6.367l1.746-1.727q.14-.14.341-.15q.202-.01.371.16q.156.156.156.35t-.16.354l-2.389 2.388q-.242.242-.565.242t-.565-.242M4.5 20q-.213 0-.356-.144T4 19.499t.144-.356T4.5 19h15q.213 0 .356.144t.144.357t-.144.356T19.5 20z");
}

</style>
