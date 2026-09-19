<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pgl4egbpm"/><path class="fhud70brn"/><path class="wh66r-6yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:prohibited" /></template>
<style>
.fhud70brn {
  fill: var(--svg-color--be1e2d, #be1e2d);
  d: path("M31.961 0C14.343 0 .008 14.335.008 31.953s14.335 31.953 31.953 31.953s31.952-14.335 31.952-31.953S49.578 0 31.961 0m0 55.986c-13.253 0-24.03-10.78-24.03-24.03s10.781-24.04 24.03-24.04c13.254 0 24.03 10.783 24.03 24.04s-10.78 24.03-24.03 24.03");
}

.pgl4egbpm {
  fill: var(--svg-color--8b182c, #8b182c);
  d: path("M53.23 47.613Q34.762 29.149 16.291 10.677c-5.481-5.481-11.09.129-5.608 5.61l36.935 36.937c5.483 5.484 11.09-.128 5.612-5.611");
}

.wh66r-6yw {
  fill: var(--svg-color--8b182c, #8b182c);
  d: path("M4.703 31.953c0-16.825 13.08-30.622 29.603-31.833c-.78-.057-1.559-.12-2.353-.12C14.335 0 0 14.335 0 31.953s14.335 31.953 31.953 31.953c.793 0 1.573-.062 2.353-.12c-16.523-1.211-29.603-15.01-29.603-31.833M34.31 55.867a24 24 0 0 0 2.351.119c13.252 0 24.03-10.78 24.03-24.03S49.91 7.916 36.661 7.916c-.793 0-1.577.043-2.351.12c12.15 1.186 21.682 11.456 21.682 23.916S46.461 54.68 34.311 55.866");
}

</style>
