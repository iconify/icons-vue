<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="pe6arpsud"/><path class="kjy2ifb4p"/><path class="fla2ngb5u"/><path class="lrk6h8atk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:three-thirty" /></template>
<style>
.fla2ngb5u {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M33.738 52.741c0 1.434-.844 2.594-1.883 2.594s-1.883-1.16-1.883-2.594V31.746c0-1.436.844-2.593 1.883-2.593s1.883 1.158 1.883 2.593z");
}

.kjy2ifb4p {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M31.869 0C14.297 0 0 14.295 0 31.869c0 17.57 14.297 31.865 31.869 31.865s31.865-14.295 31.865-31.865C63.734 14.295 49.439 0 31.869 0m0 57.53c-14.15 0-25.665-11.514-25.665-25.665S17.717 6.2 31.869 6.2c14.15 0 25.663 11.513 25.663 25.665c-.001 14.15-11.512 25.665-25.663 25.665");
}

.lrk6h8atk {
  fill: var(--svg-color--788288, #788288);
  d: path("M47.76 28.99c1.432 0 2.594.844 2.594 1.881c0 1.039-1.164 1.883-2.596 1.883l-15.195.006c-1.429 0-2.591-.846-2.589-1.883c-.002-1.039 1.161-1.883 2.589-1.885z");
}

.pe6arpsud {
  cx: 31.867px;
  cy: 31.867px;
  r: 29.521px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

</style>
